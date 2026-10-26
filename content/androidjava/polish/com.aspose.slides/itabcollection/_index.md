---
title: ITabCollection
second_title: Aspose.Slides dla Androida - odniesienie do API języka Java
description: Reprezentuje kolekcję tabulacji.
type: docs
url: /pl/com.aspose.slides/itabcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Reprezentuje kolekcję tabulacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [add(double position, int align)](#add-double-int-) | Dodaje Tab do kolekcji. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Dodaje Tab do kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element pod określonym indeksem w kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```


Pobiera element pod określonym indeksem. Tylko do odczytu [ITab](../../com.aspose.slides/itab).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```


Dodaje Tab do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | double | Pozycja Tab. |
| align | int | Wyrównanie Tab. |

**Zwraca:**
[ITab](../../com.aspose.slides/itab) - Dodany tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```


Dodaje Tab do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Obiekt Tab, który ma zostać dodany na końcu kolekcji. |

**Zwraca:**
int - Indeks, pod którym tab został dodany.
### clear() {#clear--}
```
public abstract void clear()
```


Usuwa wszystkie elementy z kolekcji.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Usuwa element pod określonym indeksem w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |