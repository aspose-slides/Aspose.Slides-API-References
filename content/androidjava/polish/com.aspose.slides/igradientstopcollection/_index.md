---
title: IGradientStopCollection
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Reprezentuje kolekcję punktów gradientu.
type: docs
url: /pl/com.aspose.slides/igradientstopcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Reprezentuje kolekcję punktów gradientu.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca punkt gradientu według indeksu. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Tworzy nowy punkt gradientu i wstawia go pod wskazanym indeksem w kolekcji. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Tworzy nowy punkt gradientu i wstawia go pod wskazanym indeksem w kolekcji. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Tworzy nowy punkt gradientu i wstawia go pod wskazanym indeksem w kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa punkt gradientu pod wskazanym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie punkty gradientu z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Zwraca punkt gradientu według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | float | Pozycja nowego punktu gradientu. |
| color | java.lang.Integer | Kolor nowego punktu gradientu. |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks nowego punktu gradientu w kolekcji.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | float | Pozycja nowego punktu gradientu. |
| presetColor | int | Kolor nowego punktu gradientu. |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks nowego punktu gradientu w kolekcji.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | float | Pozycja nowego punktu gradientu. |
| schemeColor | int | Kolor nowego punktu gradientu. |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks nowego punktu gradientu w kolekcji.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

Tworzy nowy punkt gradientu i wstawia go pod wskazanym indeksem w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks w kolekcji, w którym zostanie wstawiony nowy punkt gradientu. |
| position | float | Pozycja nowego punktu gradientu. |
| color | java.lang.Integer | Kolor nowego punktu gradientu. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Tworzy nowy punkt gradientu i wstawia go pod wskazanym indeksem w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks w kolekcji, w którym zostanie wstawiony nowy punkt gradientu. |
| position | float | Pozycja nowego punktu gradientu. |
| presetColor | int | Kolor nowego punktu gradientu. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Tworzy nowy punkt gradientu i wstawia go pod wskazanym indeksem w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks w kolekcji, w którym zostanie wstawiony nowy punkt gradientu. |
| position | float | Pozycja nowego punktu gradientu. |
| schemeColor | int | Kolor nowego punktu gradientu. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa punkt gradientu pod wskazanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks punktu gradientu, który ma zostać usunięty. |

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie punkty gradientu z kolekcji.