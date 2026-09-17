---
title: compress_image method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden auch beschnittene Bereiche gelöscht.

### Rückgabewert

Ein **bool**, das angibt, ob das Bild erfolgreich komprimiert wurde. Gibt **True** zurück, wenn das Bild skaliert oder beschnitten wurde, andernfalls **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Wenn true, entfernt die Methode die beschnittenen Bereiche des Bildes, wodurch die Größe weiter reduziert werden kann. |
| resolution | [`PicturesCompression`](/slides/python-net/de/aspose.slides.export/picturescompression) | Die gewünschte Auflösung für die Komprimierung, angegeben als Wert der [`PicturesCompression`](/slides/python-net/de/aspose.slides.export/picturescompression)-Aufzählung. |

### Anmerkungen

Diese Methode ändert die Größe und Auflösung des Bildes, ähnlich wie die Funktion „Picture Format -> Compress Pictures“ in PowerPoint.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die Auflösung kein gültiger Wert ist. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden auch beschnittene Bereiche gelöscht.

### Rückgabewert

Ein **bool**, das angibt, ob das Bild erfolgreich komprimiert wurde. Gibt **True** zurück, wenn das Bild skaliert oder beschnitten wurde, andernfalls **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Wenn true, entfernt die Methode die beschnittenen Bereiche des Bildes, wodurch die Größe weiter reduziert werden kann. |
| resolution | **float** | Die Zielauflösung in DPI. Dieser Wert muss positiv sein und definiert, wie das Bild skaliert wird. |

### Anmerkungen

Diese Methode ändert die Größe und Auflösung des Bildes, ähnlich wie die Funktion „Picture Format -> Compress Pictures“ in PowerPoint.

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn die Auflösung kein positiver Wert ist. |



### Siehe auch
* Klasse [`IPictureFillFormat`](/slides/python-net/de/aspose.slides/ipicturefillformat)
* Aufzählung [`PicturesCompression`](/slides/python-net/de/aspose.slides.export/picturescompression)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)