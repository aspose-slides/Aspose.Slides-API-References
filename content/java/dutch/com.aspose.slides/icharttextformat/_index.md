---
title: IChartTextFormat
second_title: Aspose.Slides for Java API-referentie
description: Diagram werkt met een beperkte set texteigenschappen.
type: docs
url: /nl/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Diagram werkt met een beperkte set texteigenschappen. De interfaces IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat beschrijven deze beperkte set.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Retourneert het formaat voor de tekstelementen van het diagram. |
| [getParagraphFormat()](#getParagraphFormat--) | Retourneert alinea-indeling. |
| [getPortionFormat()](#getPortionFormat--) | Retourneert deelindeling. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopieert texteigenschappen naar het opgegeven tekstframe. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopieert texteigenschappen van het opgegeven tekstframe. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Retourneert het formaat voor de tekstelementen van het diagram. Alleen-lezen [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Retour:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

Retourneert alinea-indeling. Alleen-lezen [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Retour:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

Retourneert deelindeling. Alleen-lezen [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Retour:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

Kopieert texteigenschappen naar het opgegeven tekstframe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Tekstframe om texteigenschappen naartoe te kopiëren. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

Kopieert texteigenschappen van het opgegeven tekstframe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Tekstframe waarvan texteigenschappen gekopieerd worden. |