---
title: get_image method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iparagraph/get_image/
weight: 10
---
## get_image {#}
Gibt ein Bild des Absatzes zurück.

### Rückgabe

Ein Bild, das den gerenderten Absatz enthält, oder **None**
             wenn der Absatz in seiner übergeordneten Sammlung nicht gefunden werden kann, keine gültigen
             Rendering-Grenzen hat, oder ein Fehler beim Rendern des Bildes auftritt.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Gibt ein Bild des Absatzes mit dem angegebenen Maßstab zurück.

### Rückgabe

Ein Bild, das den gerenderten Absatz enthält, oder **None**
             wenn der Absatz in seiner übergeordneten Sammlung nicht gefunden werden kann, keine gültigen
             Rendering-Grenzen hat, oder ein Fehler beim Rendern des Bildes auftritt.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scale_x | **float** | Der horizontale Skalierungsfaktor, der auf das Bild des Absatzes angewendet wird. |
| scale_y | **float** | Der vertikale Skalierungsfaktor, der auf das Bild des Absatzes angewendet wird. |



### Siehe auch
* Klasse [`IImage`](/slides/python-net/de/aspose.slides/iimage)
* Klasse [`IParagraph`](/slides/python-net/de/aspose.slides/iparagraph)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)