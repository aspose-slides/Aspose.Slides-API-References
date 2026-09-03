---
title: get_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image {#}
Returnerar en bild av paragrafen.

### Returnerar

En bild som innehåller den renderade paragrafen, eller **None**
             om paragrafen inte kan hittas i sin föräldrakollektion, saknar giltiga
             renderingsgränser, eller ett fel uppstår vid renderingen av bilden.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Returnerar en bild av paragrafen med den angivna skalan.

### Returnerar

En bild som innehåller den renderade paragrafen, eller **None**
             om paragrafen inte kan hittas i sin föräldrakollektion, saknar giltiga
             renderingsgränser, eller ett fel uppstår vid renderingen av bilden.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scale_x | **float** | Den horisontella skalningsfaktorn som tillämpas på paragrafens bild. |
| scale_y | **float** | Den vertikala skalningsfaktorn som tillämpas på paragrafens bild. |



### Se också
* klass [`IImage`](/slides/python-net/sv/aspose.slides/iimage)
* klass [`IParagraph`](/slides/python-net/sv/aspose.slides/iparagraph)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)