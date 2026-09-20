---
title: compress_image method
second_title: Aspose.Slides pro Python přes .NET API
description: 
type: docs
url: /cs/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti.

### Návratová hodnota

Bool indikující, zda byl obrázek úspěšně komprimován. Vrací **True**, pokud byl obrázek změněn velikostně nebo oříznut, jinak **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Pokud je true, metoda odstraní oříznuté oblasti obrázku, což může další snížením velikosti. |
| resolution | [`PicturesCompression`](/slides/python-net/cs/aspose.slides.export/picturescompression) | Cílové rozlišení pro kompresi, určené jako hodnota výčtu [`PicturesCompression`](/slides/python-net/cs/aspose.slides.export/picturescompression). |

### Poznámky

Tato metoda mění velikost a rozlišení obrázku podobně jako funkce PowerPointu „Formát obrázku -> Komprimovat obrázky“.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, když rozlišení není platná hodnota. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti.

### Návratová hodnota

Bool indikující, zda byl obrázek úspěšně komprimován. Vrací **True**, pokud byl obrázek změněn velikostně nebo oříznut, jinak **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Pokud je true, metoda odstraní oříznuté oblasti obrázku, což může další snížením velikosti. |
| resolution | **float** | Cílové rozlišení v DPI. Tato hodnota musí být kladná a určuje, jak bude obrázek změněn velikostně. |

### Poznámky

Tato metoda mění velikost a rozlišení obrázku podobně jako funkce PowerPointu „Formát obrázku -> Komprimovat obrázky“.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, když rozlišení není kladná hodnota. |

### Viz také
* třída [`PictureFillFormat`](/slides/python-net/cs/aspose.slides/picturefillformat)
* výčet [`PicturesCompression`](/slides/python-net/cs/aspose.slides.export/picturescompression)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)