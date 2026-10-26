---
title: compress_image method
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Kompresuje obraz, zmniejszając jego rozmiar na podstawie rozmiaru kształtu oraz określonej rozdzielczości. Opcjonalnie usuwa również przycięte obszary.

### Zwraca

Wartość **bool** wskazująca, czy obraz został pomyślnie skompresowany. Zwraca **True**, jeśli obraz został zmieniony rozmiar lub przycięty, w przeciwnym razie **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Jeśli true, metoda usunie przycięte obszary obrazu, co może dodatkowo zmniejszyć jego rozmiar. |
| resolution | [`PicturesCompression`](/slides/python-net/pl/aspose.slides.export/picturescompression) | Docelowa rozdzielczość dla kompresji, określona jako wartość wyliczenia [`PicturesCompression`](/slides/python-net/pl/aspose.slides.export/picturescompression). |

### Uwagi

Ta metoda zmienia rozmiar i rozdzielczość obrazu podobnie jak funkcja PowerPoint „Picture Format -> Compress Pictures”.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, gdy rozdzielczość nie jest prawidłową wartością. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Kompresuje obraz, zmniejszając jego rozmiar na podstawie rozmiaru kształtu oraz określonej rozdzielczości. Opcjonalnie usuwa również przycięte obszary.

### Zwraca

Wartość **bool** wskazująca, czy obraz został pomyślnie skompresowany. Zwraca **True**, jeśli obraz został zmieniony rozmiar lub przycięty, w przeciwnym razie **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Jeśli true, metoda usunie przycięte obszary obrazu, co może dodatkowo zmniejszyć jego rozmiar. |
| resolution | **float** | Docelowa rozdzielczość w DPI. Wartość ta musi być dodatnia i określa, jak obraz zostanie przeskalowany. |

### Uwagi

Ta metoda zmienia rozmiar i rozdzielczość obrazu podobnie jak funkcja PowerPoint „Picture Format -> Compress Pictures”.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Rzucany, gdy rozdzielczość nie jest dodatnią wartością. |



### Zobacz także
* klasa [`IPictureFillFormat`](/slides/python-net/pl/aspose.slides/ipicturefillformat)
* enumeracja [`PicturesCompression`](/slides/python-net/pl/aspose.slides.export/picturescompression)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)