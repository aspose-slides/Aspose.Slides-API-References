---
title: Row
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een rij in een tabel.
type: docs
url: /nl/com.aspose.slides/row/
---
**Erfenis:**  
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Alle geïmplementeerde interfaces:**  
[com.aspose.slides.IRow](../../com.aspose.slides/irow)  
```
public final class Row extends CellCollection implements IRow
```

Vertegenwoordigt een rij in een tabel.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getHeight()](#getHeight--) | Retourneert de hoogte van een rij. |
| [getMinimalHeight()](#getMinimalHeight--) | Retourneert of stelt de minimaal mogelijke hoogte van een rij in. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Retourneert of stelt de minimaal mogelijke hoogte van een rij in. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Stelt de gedefinieerde gedeelte-opmaak eigenschappen in voor alle delen van de cellen in de rij. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Stelt de gedefinieerde alinea-opmaak eigenschappen in voor alle alinea's van de cellen in de rij. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Stelt de gedefinieerde tekstkader-opmaak eigenschappen in voor alle tekstkaders van de cellen in de rij. |
| [getRowFormat()](#getRowFormat--) | Retourneert het RowFormat-object dat opmaak eigenschappen voor deze rij bevat. |

### getHeight() {#getHeight--}
```
public final double getHeight()
```

Retourneert de hoogte van een rij. Alleen-lezen double.

**Retourneert:**  
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Retourneert of stelt de minimaal mogelijke hoogte van een rij in. Lezen/Schrijven double.

**Retourneert:**  
double

### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Retourneert of stelt de minimaal mogelijke hoogte van een rij in. Lezen/Schrijven double.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Stelt de gedefinieerde gedeelte-opmaak eigenschappen in voor alle delen van de cellen in de rij.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat-object met de nodige eigenschappen ingesteld. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Stelt de gedefinieerde alinea-opmaak eigenschappen in voor alle alinea's van de cellen in de rij.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat-object met de nodige eigenschappen ingesteld. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Stelt de gedefinieerde tekstkader-opmaak eigenschappen in voor alle tekstkaders van de cellen in de rij.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat-object met de nodige eigenschappen ingesteld. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Retourneert het RowFormat-object dat opmaak eigenschappen voor deze rij bevat. Alleen-lezen [IRowFormat](../../com.aspose.slides/irowformat).

**Retourneert:**  
[IRowFormat](../../com.aspose.slides/irowformat)