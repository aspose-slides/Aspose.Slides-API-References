---
title: compress_image method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Komprimerar bilden genom att minska dess storlek baserat på formens storlek och den angivna upplösningen. Eventuellt tar den också bort beskurna områden.

### Returns
Ett **bool**-värde som indikerar om bilden har komprimerats framgångsrikt. Returnerar **True** om bilden har ändrat storlek eller beskärts, annars **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Om true, tar metoden bort de beskurna områdena i bilden, vilket potentiellt ytterligare minskar dess storlek. |
| resolution | [`PicturesCompression`](/slides/python-net/sv/aspose.slides.export/picturescompression) | Måluppslösning för komprimering, angiven som ett värde av enumen [`PicturesCompression`](/slides/python-net/sv/aspose.slides.export/picturescompression). |

### Remarks
Denna metod ändrar bildens storlek och upplösning på liknande sätt som PowerPoints funktion "Picture Format -> Compress Pictures".

### Exceptions
| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när upplösningen inte är ett giltigt värde. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Komprimerar bilden genom att minska dess storlek baserat på formens storlek och den angivna upplösningen. Eventuellt tar den också bort beskurna områden.

### Returns
Ett **bool**-värde som indikerar om bilden har komprimerats framgångsrikt. Returnerar **True** om bilden har ändrat storlek eller beskärts, annars **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Om true, tar metoden bort de beskurna områdena i bilden, vilket potentiellt ytterligare minskar dess storlek. |
| resolution | **float** | Måluppslösningen i DPI. Detta värde måste vara positivt och definierar hur bilden kommer att skalas om. |

### Remarks
Denna metod ändrar bildens storlek och upplösning på liknande sätt som PowerPoints funktion "Picture Format -> Compress Pictures".

### Exceptions
| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kastas när upplösningen inte är ett positivt värde. |



### See Also
* klass [`IPictureFillFormat`](/slides/python-net/sv/aspose.slides/ipicturefillformat)
* enumeration [`PicturesCompression`](/slides/python-net/sv/aspose.slides.export/picturescompression)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)