# RecyclerView plugin

The RecyclerView is a more advanced and flexible version of ListView. It is a container for displaying large data sets that can be scrolled very efficiently by maintaining a limited number of views. 

## Installation
`tns plugin add recycler-view`

## Usage

```xml
   <Page xmlns="http://schemas.nativescript.org/tns.xsd" 
      xmlns:recyclerView="recycler-view"     
      navigatingTo="navigatingTo">
  <StackLayout>
    <recyclerView:RecyclerView items="{{ items }}" >
        <recyclerView:RecyclerView.itemTemplate>
            <StackLayout>
                  <Label text="{{ name }}" />
                  <Label text="{{ age }}"  />
            </StackLayout>
        </recyclerView:RecyclerView.itemTemplate>
     </recyclerView:RecyclerView>
  </StackLayout>
</Page>
```
