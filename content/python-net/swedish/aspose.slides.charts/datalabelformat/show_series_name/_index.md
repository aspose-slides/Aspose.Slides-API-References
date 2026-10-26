---
title: show_series_name property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name egenskap
Returnerar eller anger en Boolean för att indikera visningsbeteendet för seriens namn för dataetiketter i ett diagram. 
            True to show the series name. False to hide.
            Läs/skriv **bool**.


### Remarks

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowSeriesName property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowSeriesName property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" cause to 
            all DataLabels[i].ShowSeriesName is equal to val).

### Definition:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```


### Se också
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)