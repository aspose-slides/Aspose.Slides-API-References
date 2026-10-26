---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image(self) {#}
Returnerar en bild av stycket.

### Returnerar

En bild som innehåller det renderade stycket, eller **None**
             om stycket inte kan hittas i dess överordnade samling, saknar giltiga
             renderingsgränser, eller om ett fel uppstår vid rendering av bilden.



```python
def get_image(self):
    ...
```



## get_image(self, scale_x, scale_y) {#float-float}
Returnerar en bild av stycket med den angivna skalan.

### Returnerar

En bild som innehåller det renderade stycket, eller **None**
             om stycket inte kan hittas i dess överordnade samling, saknar giltiga
             renderingsgränser, eller om ett fel uppstår vid rendering av bilden.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scale_x | **float** | Den horisontella skalfaktorn som tillämpas på bilden av stycket. |
| scale_y | **float** | Den vertikala skalfaktorn som tillämpas på bilden av stycket. |



### Se även
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* klass [`Paragraph`](/slides/python-net/sv/aspose.slides/paragraph)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)