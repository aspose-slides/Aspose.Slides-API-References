---
title: compress_image method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
A képet a forma mérete és a megadott felbontás alapján csökkenti. Opcionálisan a levágott területeket is eltávolítja.

### Visszatérési érték

Egy **bool** érték, amely jelzi, hogy a kép sikeresen tömörítve lett-e. **True** értéket ad vissza, ha a képet átméretezték vagy levágták, egyébként **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Ha igaz, a metódus eltávolítja a kép levágott területeit, ami tovább csökkentheti a méretét. |
| resolution | [`PicturesCompression`](/slides/python-net/hu/aspose.slides.export/picturescompression) | A tömörítés célfelbontása, amely a [`PicturesCompression`](/slides/python-net/hu/aspose.slides.export/picturescompression) enumeráció egy értéke. |

### Megjegyzések

Ez a metódus módosítja a kép méretét és felbontását, hasonlóan a PowerPoint „Kép formátum → Képek tömörítése” funkciójához.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a felbontás nem érvényes érték. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
A képet a forma mérete és a megadott felbontás alapján csökkenti. Opcionálisan a levágott területeket is eltávolítja.

### Visszatérési érték

Egy **bool** érték, amely jelzi, hogy a kép sikeresen tömörítve lett-e. **True** értéket ad vissza, ha a képet átméretezték vagy levágták, egyébként **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Ha igaz, a metódus eltávolítja a kép levágott területeit, ami tovább csökkentheti a méretét. |
| resolution | **float** | A célfelbontás DPI-ben. Ennek az értéknek pozitívnak kell lennie, és meghatározza, hogyan lesz átméretezve a kép. |

### Megjegyzések

Ez a metódus módosítja a kép méretét és felbontását, hasonlóan a PowerPoint „Kép formátum → Képek tömörítése” funkciójához.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a felbontás nem pozitív érték. |



### Lásd még
* osztály [`PictureFillFormat`](/slides/python-net/hu/aspose.slides/picturefillformat)
* enumeráció [`PicturesCompression`](/slides/python-net/hu/aspose.slides.export/picturescompression)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)