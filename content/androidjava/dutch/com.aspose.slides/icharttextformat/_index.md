---
title: IChartTextFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Grafiek werkt met een beperkte set tekstopmaak-eigenschappen.
type: docs
url: /nl/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Grafiek werkt met een beperkte set tekstopmaak-eigenschappen. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat interfaces beschrijven deze beperkte set.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Retourneert de opmaak voor de tekstelementen van de grafiek. |
| [getParagraphFormat()](#getParagraphFormat--) | Retourneert alinea-opmaak. |
| [getPortionFormat()](#getPortionFormat--) | Retourneert gedeelte-opmaak. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopieert tekstopmaak naar het gespecificeerde tekstkader. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopieert tekstopmaak van het gespecificeerde tekstkader. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Retourneert de opmaak voor de tekstelementen van de grafiek. Alleen-lezen [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Retourneert:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Retourneert alinea-opmaak. Alleen-lezen [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Retourneert:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Retourneert gedeelte-opmaak. Alleen-lezen [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Retourneert:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


Kopieert tekstopmaak naar het gespecificeerde tekstkader.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Tekstkader om tekstopmaak naartoe te kopiëren. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Kopieert tekstopmaak van het gespecificeerde tekstkader.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Tekstkader om tekstopmaak te kopiëren. |