---
title: compress_image method
second_title: Aspose.Slides a Pythonhoz .NET API referenciája
description: 
type: docs
url: /hu/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
A képet a méret csökkentésével, a alakzat mérete és a megadott felbontás alapján tömöríti. Opcionálisan törli a levágott területeket is.

### Visszatérési érték

Egy **bool**, amely azt jelzi, hogy a képet sikeresen tömörítették-e. **True** értéket ad vissza, ha a képet átméretezték vagy levágták, egyébként **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Ha igaz, a metódus eltávolítja a kép levágott területeit, ami tovább csökkentheti a méretét. |
| resolution | [`PicturesCompression`](/slides/python-net/hu/aspose.slides.export/picturescompression) | A tömörítés célfelbontása, amely a [`PicturesCompression`](/slides/python-net/hu/aspose.slides.export/picturescompression) enumeráció egy értéke. |

### Megjegyzés

Ez a metódus módosítja a kép méretét és felbontását, hasonlóan a PowerPoint „Képformátum -> Képek tömörítése” funkciójához.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a felbontás nem érvényes érték. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
A képet a méret csökkentésével, a alakzat mérete és a megadott felbontás alapján tömöríti. Opcionálisan törli a levágott területeket is.

### Visszatérési érték

Egy **bool**, amely azt jelzi, hogy a képet sikeresen tömörítették-e. **True** értéket ad vissza, ha a képet átméretezték vagy levágták, egyébként **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Ha igaz, a metódus eltávolítja a kép levágott területeit, ami tovább csökkentheti a méretét. |
| resolution | **float** | A célfelbontás DPI-ben. Ennek az értéknek pozitívnak kell lennie, és meghatározza, hogyan lesz a kép átméretezve. |

### Megjegyzés

Ez a metódus módosítja a kép méretét és felbontását, hasonlóan a PowerPoint „Képformátum -> Képek tömörítése” funkciójához.

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Kivétel, ha a felbontás nem pozitív érték. |



### Lásd még
* osztály [`IPictureFillFormat`](/slides/python-net/hu/aspose.slides/ipicturefillformat)
* enumeráció [`PicturesCompression`](/slides/python-net/hu/aspose.slides.export/picturescompression)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)