---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
Returnerar en bild av paragrafen.

### Returnerar

En bild som innehåller den renderade paragrafen, eller **None**
             om paragrafen inte kan hittas i sin överordnade samling, saknar giltiga
             renderingsgränser, eller om ett fel uppstår vid rendering av bilden.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Returnerar en bild av paragrafen med den angivna skalningen.

### Returnerar

En bild som innehåller den renderade paragrafen, eller **None**
             om paragrafen inte kan hittas i sin överordnade samling, saknar giltiga
             renderingsgränser, eller om ett fel uppstår vid rendering av bilden.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scale_x | **float** | Den horisontella skalfaktorn som tillämpas på paragrafbilden. |
| scale_y | **float** | Den vertikala skalfaktorn som tillämpas på paragrafbilden. |



### Se även
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* klass [`Paragraph`](/slides/python-net/sv/aspose.slides/paragraph)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)