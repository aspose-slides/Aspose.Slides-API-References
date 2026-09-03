---
title: get_image method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/paragraph/get_image/
weight: 20
---
## get_image {#}
Gibt ein Bild des Absatzes zurück.

### Rückgabewert

Ein Bild, das den gerenderten Absatz enthält, oder **None**
             wenn der Absatz in seiner übergeordneten Sammlung nicht gefunden werden kann, keine gültigen
             Rendergrenzen hat oder beim Rendern des Bildes ein Fehler auftritt.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Gibt ein Bild des Absatzes mit dem angegebenen Maßstab zurück.

### Rückgabewert

Ein Bild, das den gerenderten Absatz enthält, oder **None**
             wenn der Absatz in seiner übergeordneten Sammlung nicht gefunden werden kann, keine gültigen
             Rendergrenzen hat oder beim Rendern des Bildes ein Fehler auftritt.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scale_x | **float** | Der horizontale Skalierungsfaktor, der auf das Absatzbild angewendet wird. |
| scale_y | **float** | Der vertikale Skalierungsfaktor, der auf das Absatzbild angewendet wird. |



### Siehe auch
* class [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* class [`Paragraph`](/slides/python-net/de/aspose.slides/paragraph)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)