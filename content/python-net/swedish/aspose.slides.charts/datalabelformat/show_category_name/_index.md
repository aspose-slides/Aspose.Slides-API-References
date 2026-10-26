---
title: show_category_name property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name egenskap
Representerar beteendet för hur kategorinamnet för datamärkning visas i ett specificerat diagram.
            True för att visa kategorinamnet för datamärkena i ett diagram. False för att dölja.
            Läs/skriv **bool**.

### Anmärkningar
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowCategoryName property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowCategoryName property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" cause to 
            all DataLabels[i].ShowCategoryName is equal to val).

### Definition:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### Se även
* klass [`DataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/datalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)