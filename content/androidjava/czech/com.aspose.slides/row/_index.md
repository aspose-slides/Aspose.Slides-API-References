---
title: Row
second_title: Aspose.Slides pro Android prostřednictvím referenční příručky Java API
description: Representuje řádek v tabulce.
type: docs
url: /cs/com.aspose.slides/row/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**All Implemented Interfaces:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Represents a row in a table.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeight()](#getHeight--) | Vrací výšku řádku. |
| [getMinimalHeight()](#getMinimalHeight--) | Vrací nebo nastavuje minimální možnou výšku řádku. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Vrací nebo nastavuje minimální možnou výšku řádku. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Nastavuje definované vlastnosti formátu úseku pro všechny úseky buněk řádku. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Nastavuje definované vlastnosti formátu odstavce pro všechny odstavce buněk řádku. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Nastavuje definované vlastnosti formátu textového rámce pro všechny textové rámce buněk řádku. |
| [getRowFormat()](#getRowFormat--) | Vrací objekt RowFormat, který obsahuje formátovací vlastnosti pro tento řádek. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


Vrací výšku řádku. Pouze pro čtení double.

**Návratová hodnota:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


Vrací nebo nastavuje minimální možnou výšku řádku. Čtení a zápis double.

**Návratová hodnota:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


Vrací nebo nastavuje minimální možnou výšku řádku. Čtení a zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Nastavuje definované vlastnosti formátu úseku pro všechny úseky buněk řádku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Nastavuje definované vlastnosti formátu odstavce pro všechny odstavce buněk řádku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Nastavuje definované vlastnosti formátu textového rámce pro všechny textové rámce buněk řádku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


Vrací objekt RowFormat, který obsahuje formátovací vlastnosti pro tento řádek. Pouze pro čtení [IRowFormat](../../com.aspose.slides/irowformat).

**Návratová hodnota:**
[IRowFormat](../../com.aspose.slides/irowformat)