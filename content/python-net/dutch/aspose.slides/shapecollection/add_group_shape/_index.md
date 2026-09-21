---
title: add_group_shape method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Maakt een nieuwe lege groepsvorm en voegt deze toe aan het einde van de vormverzameling.  
Het frame van de groep past zich automatisch aan om alle toegevoegde vormen te omvatten.

### Retour

De nieuw gemaakte [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Maakt een nieuwe groepsvorm, converteert de opgegeven SVG-afbeelding naar afzonderlijke vormen, en voegt de resulterende groep toe aan het einde van de vormverzameling.

### Retour

De nieuw gemaakte [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/nl/aspose.slides/isvgimage) | De [`ISvgImage`](/slides/python-net/nl/aspose.slides/isvgimage) met vectorinhoud om te converteren naar vormen. |
| x | **float** | De x-coördinaat van het frame van de groep, in punten. |
| y | **float** | De y-coördinaat van het frame van de groep, in punten. |
| width | **float** | De breedte van het frame van de groep, in punten. |
| height | **float** | De hoogte van het frame van de groep, in punten. |



### Zie ook
* klasse [`IGroupShape`](/slides/python-net/nl/aspose.slides/igroupshape)
* klasse [`ISvgImage`](/slides/python-net/nl/aspose.slides/isvgimage)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)