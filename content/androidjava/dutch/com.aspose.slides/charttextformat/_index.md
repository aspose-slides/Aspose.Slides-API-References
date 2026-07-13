---
title: ChartTextFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert de standaardtekstopmaak voor tekstelementen van grafieken.
type: docs
url: /nl/com.aspose.slides/charttextformat/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Specificeert standaardtekstopmaak voor tekstelementen van grafieken.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopieert tekstopmaak naar opgegeven tekstframe. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopieert tekstopmaak van opgegeven tekstframe. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Alleen-lezen [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Retour:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Alleen-lezen [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Retour:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Alleen-lezen [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Retour:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Kopieert tekstopmaak naar het opgegeven tekstframe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Tekstframe om tekstopmaak naar te kopiëren. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Kopieert tekstopmaak van het opgegeven tekstframe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Tekstframe waarvan tekstopmaak wordt gekopieerd. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject