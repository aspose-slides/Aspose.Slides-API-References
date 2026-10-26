---
title: ILayoutSlideCollection
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje základní třídu pro kolekci rozložení snímků.
type: docs
url: /cs/com.aspose.slides/ilayoutslidecollection/
---
**Všechna implementovaná rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Representuje základní třídu pro kolekci rozložení snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací rozložení snímku podle indexu. |
| [getByType(byte type)](#getByType-byte-) | Vrací první rozložení snímku zadaného typu. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Odstraňuje rozložení z kolekce. |
| [removeUnused()](#removeUnused--) | Odstraňuje nepoužitá rozložení snímků (rozložení snímků, jejichž HasDependingSlides je false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Vrací rozložení snímku podle indexu. Pouze pro čtení [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

Vrací první rozložení snímku zadaného typu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | byte | Typ rozložení snímku, který se má najít. |

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) se zadaným typem nebo null, pokud nebyla nalezena žádná rozložení.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Odstraňuje rozložení z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozložení snímku, které má být odstraněno z kolekce.

--------------------

1) Aby se předešlo vyhození výjimky PptxEditException, předtím zkontrolujte vlastnost HasDependingSlides rozložení. 2) Můžete také použít metodu [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) pro zjednodušení kódu. |

### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Odstraňuje nepoužitá rozložení snímků (rozložení snímků, jejichž HasDependingSlides je false).