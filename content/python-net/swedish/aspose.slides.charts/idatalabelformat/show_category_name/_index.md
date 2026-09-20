---
title: show_category_name property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name egenskap
Representerar ett specificerat diagramdataetiketts beteende för visning av kategorinamn.
True för att visa kategorinamnet för dataetiketterna på ett diagram. False för att dölja.
Läs/skriv **bool**.

### Anmärkningar
Om föräldern till detta DataLabelFormat-objekt är en DataLabelCollection-samling av dataetiketter så får den här egenskapen eller sätter standardvärdet för ShowCategoryName-egenskapen för de nya dataetiketterna i DataLabelCollection-samlingen.
Sätt denna egenskap med ett värde sätter också detta värde till ShowCategoryName-egenskapen för alla dataetiketter i DataLabelCollection-samlingen
(t.ex. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" leder till att alla DataLabels[i].ShowCategoryName är lika med val).

### Definition:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### Se också
* klass [`IDataLabelFormat`](/slides/python-net/sv/aspose.slides.charts/idatalabelformat)
* modul [`aspose.slides.charts`](/slides/python-net/sv/aspose.slides.charts)
* bibliotek [`Aspose.Slides`](/slides/python-net)