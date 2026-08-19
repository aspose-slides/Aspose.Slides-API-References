---
title: Row
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje řádek v tabulce.
type: docs
url: /cs/com.aspose.slides/row/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Všechny implementované rozhraní:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Reprezentuje řádek v tabulce.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeight()](#getHeight--) | Vrací výšku řádku. |
| [getMinimalHeight()](#getMinimalHeight--) | Vrací nebo nastavuje minimální možnou výšku řádku. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Vrací nebo nastavuje minimální možnou výšku řádku. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Nastavuje definované vlastnosti formátu části do všech částí buněk řádku. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Nastavuje definované vlastnosti formátu odstavce do všech odstavců buněk řádku. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Nastavuje definované vlastnosti formátu textového rámce do všech textových rámců buněk řádku. |
| [getRowFormat()](#getRowFormat--) | Vrací objekt RowFormat, který obsahuje vlastnosti formátování pro tento řádek. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```

Vrací výšku řádku. Pouze ke čtení double.

**Vrací:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Vrací nebo nastavuje minimální možnou výšku řádku. Čtení/Zápis double.

**Vrací:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Vrací nebo nastavuje minimální možnou výšku řádku. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Nastavuje definované vlastnosti formátu části do všech částí buněk řádku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | objekt IPortionFormat s nastavenými potřebnými vlastnostmi. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Nastavuje definované vlastnosti formátu odstavce do všech odstavců buněk řádku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | objekt IParagraphFormat s nastavenými potřebnými vlastnostmi. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Nastavuje definované vlastnosti formátu textového rámce do všech textových rámců buněk řádku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | objekt ITextFrameFormat s nastavenými potřebnými vlastnostmi. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Vrací objekt RowFormat, který obsahuje vlastnosti formátování pro tento řádek. Pouze ke čtení [IRowFormat](../../com.aspose.slides/irowformat).

**Vrací:**
[IRowFormat](../../com.aspose.slides/irowformat)