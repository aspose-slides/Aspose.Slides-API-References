---
title: compress_image method
second_title: Aspose.Slides pro Python prostřednictvím .NET API
description: 
type: docs
url: /cs/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti.

### Návratová hodnota

Boolovská hodnota, která udává, zda byl obrázek úspěšně komprimován. Vrací **True**, pokud byl obrázek změněn velikostně nebo oříznut, jinak **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Pokud je true, metoda odstraní oříznuté oblasti obrázku, což může dále snížit jeho velikost. |
| resolution | [`PicturesCompression`](/slides/python-net/cs/aspose.slides.export/picturescompression) | Cílové rozlišení pro kompresi, uvedené jako hodnota výčtu [`PicturesCompression`](/slides/python-net/cs/aspose.slides.export/picturescompression). |

### Poznámky

Tato metoda mění velikost a rozlišení obrázku podobně jako funkce PowerPointu „Picture Format → Compress Pictures“.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud rozlišení není platná hodnota. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Komprimuje obrázek snížením jeho velikosti na základě velikosti tvaru a zadaného rozlišení. Volitelně také odstraňuje oříznuté oblasti.

### Návratová hodnota

Boolovská hodnota, která udává, zda byl obrázek úspěšně komprimován. Vrací **True**, pokud byl obrázek změněn velikostně nebo oříznut, jinak **False**.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Pokud je true, metoda odstraní oříznuté oblasti obrázku, což může dále snížit jeho velikost. |
| resolution | **float** | Cílové rozlišení v DPI. Tato hodnota musí být kladná a určuje, jak bude obrázek změněn velikostně. |

### Poznámky

Tato metoda mění velikost a rozlišení obrázku podobně jako funkce PowerPointu „Picture Format → Compress Pictures“.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Vyvolána, pokud rozlišení není kladná hodnota. |



### Viz také
* třída [`IPictureFillFormat`](/slides/python-net/cs/aspose.slides/ipicturefillformat)
* výčet [`PicturesCompression`](/slides/python-net/cs/aspose.slides.export/picturescompression)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)