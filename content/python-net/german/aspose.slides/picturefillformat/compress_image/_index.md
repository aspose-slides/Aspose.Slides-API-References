---
title: compress_image method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden dabei zugeschnittene Bereiche gelöscht.

### Rückgabewert

Ein **bool**, der angibt, ob das Bild erfolgreich komprimiert wurde. Gibt **True** zurück, wenn das Bild skaliert oder beschnitten wurde, andernfalls **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Wenn true, entfernt die Methode die zugeschnittenen Bildbereiche, was die Dateigröße weiter reduzieren kann. |
| resolution | [`PicturesCompression`](/slides/python-net/de/aspose.slides.export/picturescompression) | Die Zielauflösung für die Kompression, angegeben als Wert der [`PicturesCompression`](/slides/python-net/de/aspose.slides.export/picturescompression)-Aufzählung. |

### Hinweise

Diese Methode ändert die Größe und Auflösung des Bildes ähnlich wie die PowerPoint-Funktion „Picture Format -> Compress Pictures“.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die Auflösung kein gültiger Wert ist. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden dabei zugeschnittene Bereiche gelöscht.

### Rückgabewert

Ein **bool**, der angibt, ob das Bild erfolgreich komprimiert wurde. Gibt **True** zurück, wenn das Bild skaliert oder beschnitten wurde, andernfalls **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Wenn true, entfernt die Methode die zugeschnittenen Bildbereiche, was die Dateigröße weiter reduzieren kann. |
| resolution | **float** | Die Zielauflösung in DPI. Dieser Wert muss positiv sein und definiert, wie das Bild skaliert wird. |

### Hinweise

Diese Methode ändert die Größe und Auflösung des Bildes ähnlich wie die PowerPoint-Funktion „Picture Format -> Compress Pictures“.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die Auflösung kein positiver Wert ist. |



### Siehe auch
* class [`PictureFillFormat`](/slides/python-net/de/aspose.slides/picturefillformat)
* enumeration [`PicturesCompression`](/slides/python-net/de/aspose.slides.export/picturescompression)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)