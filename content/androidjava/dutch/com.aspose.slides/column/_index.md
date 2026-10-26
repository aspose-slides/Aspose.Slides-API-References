---
title: Column
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een kolom in een tabel voor.
type: docs
url: /nl/com.aspose.slides/column/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Stelt een kolom in een tabel voor.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getWidth()](#getWidth--) | Retourneert of stelt de breedte van een kolom in. |
| [setWidth(double value)](#setWidth-double-) | Retourneert of stelt de breedte van een kolom in. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Stelt de gedefinieerde portionformatteereigenschappen in voor alle portion van kolomcellen. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Stelt de gedefinieerde alinea-formatteereigenschappen in voor alle alinea’s van kolomcellen. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Stelt de gedefinieerde tekstkader-formatteereigenschappen in voor alle tekstkaders van kolomcellen. |
| [getColumnFormat()](#getColumnFormat--) | Retourneert het ColumnFormat-object dat opmaakproperties voor deze kolom bevat. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Retourneert of stelt de breedte van een kolom in. Lezen/schrijven double.

**Retour:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Retourneert of stelt de breedte van een kolom in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Stelt de gedefinieerde portionformatteereigenschappen in voor alle portion van kolomcellen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat-object met de benodigde eigenschappen ingesteld. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Stelt de gedefinieerde alinea-formatteereigenschappen in voor alle alinea’s van kolomcellen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat-object met de benodigde eigenschappen ingesteld. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```


Stelt de gedefinieerde tekstkader-formatteereigenschappen in voor alle tekstkaders van kolomcellen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat-object met de benodigde eigenschappen ingesteld. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


Retourneert het ColumnFormat-object dat opmaakproperties voor deze kolom bevat. Alleen-lezen [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Retour:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)