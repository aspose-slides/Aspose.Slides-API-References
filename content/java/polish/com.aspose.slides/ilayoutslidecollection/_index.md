---
title: ILayoutSlideCollection
second_title: Aspose.Slides dla Java – Odnośnik API
description: Reprezentuje klasę bazową dla kolekcji slajdów układu.
type: docs
url: /pl/com.aspose.slides/ilayoutslidecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Represents a base class for collection of a layout slides.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca slajd układu według indeksu. |
| [getByType(byte type)](#getByType-byte-) | Zwraca pierwszy slajd układu określonego typu. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Usuwa układ z kolekcji. |
| [removeUnused()](#removeUnused--) | Usuwa nieużywane slajdy układu (slajdy układu, których HasDependingSlides jest false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Zwraca slajd układu według indeksu. Tylko do odczytu [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


Zwraca pierwszy slajd układu określonego typu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | byte | Typ slajdu układu do znalezienia. |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) o określonym typie lub null, jeśli nie znaleziono układów.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


Usuwa układ z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd układu do usunięcia z kolekcji.

--------------------

1) Aby uniknąć wyrzucenia PptxEditException, sprawdź wcześniej właściwość HasDependingSlides układu. 2) Można również użyć metody [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove), aby uprościć kod. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Usuwa nieużywane slajdy układu (slajdy układu, których HasDependingSlides jest false).