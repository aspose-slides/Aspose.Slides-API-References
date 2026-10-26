---
title: IGradientStopCollection
second_title: Aspose.Slides dla Java – referencja API
description: Reprezentuje kolekcję przystanków gradientu.
type: docs
url: /pl/com.aspose.slides/igradientstopcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Reprezentuje kolekcję przystanków gradientu.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca przystanek gradientu według indeksu. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | Tworzy nowy przystanek gradientu i dodaje go na koniec kolekcji. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Tworzy nowy przystanek gradientu i dodaje go na koniec kolekcji. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Tworzy nowy przystanek gradientu i dodaje go na koniec kolekcji. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | Tworzy nowy przystanek gradientu i wstawia go w określonym indeksie do kolekcji. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Tworzy nowy przystanek gradientu i wstawia go w określonym indeksie do kolekcji. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Tworzy nowy przystanek gradientu i wstawia go w określonym indeksie do kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa przystanek gradientu pod określonym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie przystanki gradientu z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

Zwraca przystanek gradientu według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

Tworzy nowy przystanek gradientu i dodaje go na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | float | Pozycja nowego przystanku gradientu. |
| color | java.awt.Color | Kolor nowego przystanku gradientu. |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks nowego przystanku gradientu w kolekcji.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

Tworzy nowy przystanek gradientu i dodaje go na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | float | Pozycja nowego przystanku gradientu. |
| presetColor | int | Kolor nowego przystanku gradientu. |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks nowego przystanku gradientu w kolekcji.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

Tworzy nowy przystanek gradientu i dodaje go na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | float | Pozycja nowego przystanku gradientu. |
| schemeColor | int | Kolor nowego przystanku gradientu. |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks nowego przystanku gradientu w kolekcji.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

Tworzy nowy przystanek gradientu i wstawia go w określonym indeksie do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks w kolekcji, w którym nowy przystanek gradientu zostanie wstawiony. |
| position | float | Pozycja nowego przystanku gradientu. |
| color | java.awt.Color | Kolor nowego przystanku gradientu. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

Tworzy nowy przystanek gradientu i wstawia go w określonym indeksie do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks w kolekcji, w którym nowy przystanek gradientu zostanie wstawiony. |
| position | float | Pozycja nowego przystanku gradientu. |
| presetColor | int | Kolor nowego przystanku gradientu. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

Tworzy nowy przystanek gradientu i wstawia go w określonym indeksie do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks w kolekcji, w którym nowy przystanek gradientu zostanie wstawiony. |
| position | float | Pozycja nowego przystanku gradientu. |
| schemeColor | int | Kolor nowego przystanku gradientu. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa przystanek gradientu pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks przystanku gradientu, który ma zostać usunięty. |

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie przystanki gradientu z kolekcji.