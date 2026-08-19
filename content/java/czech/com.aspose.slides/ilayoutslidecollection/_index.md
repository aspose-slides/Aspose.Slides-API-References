---
title: ILayoutSlideCollection
second_title: Aspose.Slides pro Java API Reference
description: Představuje základní třídu pro kolekci rozvržení snímků.
type: docs
url: /cs/com.aspose.slides/ilayoutslidecollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Představuje základní třídu pro kolekci rozvržení snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací rozvržení snímku podle indexu. |
| [getByType(byte type)](#getByType-byte-) | Vrací první rozvržení snímku daného typu. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Odstraňuje rozvržení z kolekce. |
| [removeUnused()](#removeUnused--) | Odstraňuje nepoužité rozvržení snímků (rozvržení snímků, jejichž HasDependingSlides je false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Vrací rozvržení snímku podle indexu. Jen pro čtení [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


Vrací první rozvržení snímku daného typu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | byte | Typ rozvržení snímku k vyhledání. |

**Vrací:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) with specified type or null if no layouts found.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


Odstraňuje rozvržení z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozvržení snímku k odstranění z kolekce.

--------------------

1) Aby se předešlo vyhození výjimky PptxEditException, předtím zkontrolujte vlastnost HasDependingSlides rozvržení. 2) Můžete také použít metodu [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) k zjednodušení kódu.
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Odstraňuje nepoužité rozvržení snímků (rozvržení snímků, jejichž HasDependingSlides je false).