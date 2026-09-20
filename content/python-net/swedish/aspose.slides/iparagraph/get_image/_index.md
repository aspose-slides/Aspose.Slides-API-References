---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image(self) {#}
Returnerar en bild av stycket.

### Returnerar

En bild som innehåller det renderade stycket, eller **None**
             om stycket inte kan hittas i sin föräldrainsamling, saknar giltiga renderingsgränser, eller ett fel inträffar vid rendering av bilden.



```python
def get_image(self):
    ...
```



## get_image(self, scale_x, scale_y) {#float-float}
Returnerar en bild av stycket med den angivna skalan.

### Returnerar

En bild som innehåller det renderade stycket, eller **None**
             om stycket inte kan hittas i sin föräldrainsamling, saknar giltiga renderingsgränser, eller ett fel inträffar vid rendering av bilden.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scale_x | **float** | Den horisontella skalningsfaktorn som tillämpas på styckebilden. |
| scale_y | **float** | Den vertikala skalningsfaktorn som tillämpas på styckebilden. |



### Se även
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* klass [`IParagraph`](/slides/python-net/sv/aspose.slides/iparagraph)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)