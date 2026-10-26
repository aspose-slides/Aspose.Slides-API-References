---
title: Column
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een kolom in een tabel.
type: docs
url: /nl/com.aspose.slides/column/
---
**Overerving:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Stelt een kolom in een tabel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getWidth()](#getWidth--) | Retourneert of stelt de breedte van een kolom in. |
| [setWidth(double value)](#setWidth-double-) | Retourneert of stelt de breedte van een kolom in. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Stelt gedefinieerde deelopmaak-eigenschappen in voor alle kolomcellen-gedeelten. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Stelt gedefinieerde alinea-opmaak-eigenschappen in voor alle kolomcellen-alinea's. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Stelt gedefinieerde tekstframe-opmaak-eigenschappen in voor alle kolomcellen-tekstframes. |
| [getColumnFormat()](#getColumnFormat--) | Retourneert het ColumnFormat-object dat opmaak-eigenschappen bevat voor deze kolom. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Retourneert of stelt de breedte van een kolom in. Lezen/Schrijven double.

**Retourneert:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

Retourneert of stelt de breedte van een kolom in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Stelt gedefinieerde deelopmaak-eigenschappen in voor alle kolomcellen-gedeelten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object met de nodige eigenschappen ingesteld. |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Stelt gedefinieerde alinea-opmaak-eigenschappen in voor alle kolomcellen-alinea's.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object met de nodige eigenschappen ingesteld. |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```

Stelt gedefinieerde tekstframe-opmaak-eigenschappen in voor alle kolomcellen-tekstframes.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object met de nodige eigenschappen ingesteld. |
### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

Retourneert het ColumnFormat-object dat opmaak-eigenschappen bevat voor deze kolom. Alleen-lezen [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Retourneert:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)