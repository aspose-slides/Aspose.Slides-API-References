---
title: compress_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Valfritt tar den även bort beskurna områden.

### Returnerar

Ett **bool** som anger om bilden har komprimerats framgångsrikt. Returnerar **True** om bilden har ändrats storlek eller beskärts, annars **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Om true, kommer metoden att ta bort de beskurna områdena i bilden, vilket potentiellt ytterligare minskar dess storlek. |
| resolution | [`PicturesCompression`](/slides/python-net/sv/aspose.slides.export/picturescompression) | Måluppslösningen för komprimeringen, specificerad som ett värde i enumet [`PicturesCompression`](/slides/python-net/sv/aspose.slides.export/picturescompression). |

### Anmärkningar

Denna metod ändrar bildens storlek och upplösning liknande PowerPoints funktion "Picture Format -> Compress Pictures".

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när upplösningen inte är ett giltigt värde. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Valfritt tar den även bort beskurna områden.

### Returnerar

Ett **bool** som anger om bilden har komprimerats framgångsrikt. Returnerar **True** om bilden har ändrats storlek eller beskärts, annars **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Om true, kommer metoden att ta bort de beskurna områdena i bilden, vilket potentiellt ytterligare minskar dess storlek. |
| resolution | **float** | Måluppslösningen i DPI. Detta värde måste vara positivt och definierar hur bilden kommer att ändras storlek. |

### Anmärkningar

Denna metod ändrar bildens storlek och upplösning liknande PowerPoints funktion "Picture Format -> Compress Pictures".

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när upplösningen inte är ett positivt värde. |



### Se även
* klass [`PictureFillFormat`](/slides/python-net/sv/aspose.slides/picturefillformat)
* enumeration [`PicturesCompression`](/slides/python-net/sv/aspose.slides.export/picturescompression)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)