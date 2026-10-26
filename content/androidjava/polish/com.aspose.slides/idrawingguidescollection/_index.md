---
title: IDrawingGuidesCollection
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje kolekcję regulowanych linii pomocniczych rysowania.
type: docs
url: /pl/com.aspose.slides/idrawingguidescollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Reprezentuje kolekcję regulowanych linii pomocniczych rysowania.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca linię pomocniczą rysowania według indeksu. |
| [add(byte orientation, float position)](#add-byte-float-) | Dodaje linię pomocniczą rysowania na końcu kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa linię pomocniczą rysowania o podanym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [getCount()](#getCount--) | Pobiera liczbę wszystkich elementów w kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Zwraca linię pomocniczą rysowania według indeksu. Tylko do odczytu [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Dodaje linię pomocniczą rysowania na końcu kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| orientation | byte | Orientacja linii pomocniczej rysowania. |
| position | float | Pozycja linii pomocniczej rysowania w punktach. |

**Zwraca:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Usuwa linię pomocniczą rysowania o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks linii pomocniczej rysowania, którą należy usunąć. |

### clear() {#clear--}
```
public abstract void clear()
```


Usuwa wszystkie elementy z kolekcji.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Pobiera liczbę wszystkich elementów w kolekcji. Tylko do odczytu int.

**Zwraca:**
int