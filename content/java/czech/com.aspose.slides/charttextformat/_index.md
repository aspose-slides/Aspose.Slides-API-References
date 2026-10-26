---
title: ChartTextFormat
second_title: Aspose.Slides pro Java - referenční příručka API
description: Určuje výchozí formátování textu pro textové prvky grafu.
type: docs
url: /cs/com.aspose.slides/charttextformat/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Určuje výchozí formátování textu pro textové prvky grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopíruje formát textu do určeného textového rámce. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopíruje formát textu z určeného textového rámce. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Pouze ke čtení [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Vrací:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Pouze ke čtení [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Vrací:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Pouze ke čtení [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Vrací:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Kopíruje formát textu do určeného textového rámce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textový rámec, do kterého se má zkopírovat formát textu. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Kopíruje formát textu z určeného textového rámce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textový rámec, z kterého se má zkopírovat formát textu. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject