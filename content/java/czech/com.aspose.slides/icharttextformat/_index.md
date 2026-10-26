---
title: IChartTextFormat
second_title: Aspose.Slides pro Java API Reference
description: Diagram funguje s omezeným množstvím vlastností formátování textu.
type: docs
url: /cs/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Diagram funguje s omezeným množstvím vlastností formátování textu. Rozhraní IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat popisují tuto omezenou sadu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Vrací formát pro textové prvky diagramu. |
| [getParagraphFormat()](#getParagraphFormat--) | Vrací formát odstavce. |
| [getPortionFormat()](#getPortionFormat--) | Vrací formát úseku. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopíruje formát textu do určeného textového rámečku. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopíruje formát textu ze zadaného textového rámečku. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Vrací formát pro textové prvky diagramu. Pouze ke čtení [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Vrací:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Vrací formát odstavce. Pouze ke čtení [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Vrací:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Vrací formát úseku. Pouze ke čtení [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Vrací:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


Kopíruje formát textu do určeného textového rámečku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textový rámeček, do kterého se má formát textu zkopírovat. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Kopíruje formát textu ze zadaného textového rámečku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textový rámeček, ze kterého se má formát textu zkopírovat. |