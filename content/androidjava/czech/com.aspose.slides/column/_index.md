---
title: Column
second_title: Aspose.Slides pro Android prostřednictvím referenčního dokumentu Java API
description: Představuje sloupec v tabulce.
type: docs
url: /cs/com.aspose.slides/column/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Všechny implementované rozhraní:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Představuje sloupec v tabulce.
## Metody

| Metoda | Popis |
| --- | --- |
| [getWidth()](#getWidth--) | Vrací nebo nastavuje šířku sloupce. |
| [setWidth(double value)](#setWidth-double-) | Vrací nebo nastavuje šířku sloupce. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Nastavuje definované vlastnosti formátu části pro všechny části buněk sloupce. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Nastavuje definované vlastnosti formátu odstavce pro všechny odstavce buněk sloupce. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Nastavuje definované vlastnosti formátu textového rámce pro všechny textové rámce buněk sloupce. |
| [getColumnFormat()](#getColumnFormat--) | Vrací objekt ColumnFormat, který obsahuje formátovací vlastnosti pro tento sloupec. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Vrací nebo nastavuje šířku sloupce. Čtení / zápis double.

**Vrací:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Vrací nebo nastavuje šířku sloupce. Čtení / zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Nastavuje definované vlastnosti formátu části pro všechny části buněk sloupce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Objekt IPortionFormat s nastavenými potřebnými vlastnostmi. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Nastavuje definované vlastnosti formátu odstavce pro všechny odstavce buněk sloupce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Objekt IParagraphFormat s nastavenými potřebnými vlastnostmi. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Nastavuje definované vlastnosti formátu textového rámce pro všechny textové rámce buněk sloupce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Objekt ITextFrameFormat s nastavenými potřebnými vlastnostmi. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


Vrací objekt ColumnFormat, který obsahuje formátovací vlastnosti pro tento sloupec. Pouze pro čtení [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Vrací:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)