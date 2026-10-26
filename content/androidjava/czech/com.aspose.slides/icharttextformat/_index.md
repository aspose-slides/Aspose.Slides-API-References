---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Graf funguje s omezenou sadou vlastností formátování textu.
type: docs
url: /cs/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Graf funguje s omezenou sadou vlastností formátování textu. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat interfaces describe this restricted set.
## Metody

| Method | Description |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Vrací formát pro textové prvky grafu. |
| [getParagraphFormat()](#getParagraphFormat--) | Vrací formát odstavce. |
| [getPortionFormat()](#getPortionFormat--) | Vrací formát úseku. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopíruje formát textu do zadaného textového rámce. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopíruje formát textu ze zadaného textového rámce. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Vrací formát pro textové prvky grafu. Pouze pro čtení [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Vrací:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Vrací formát odstavce. Pouze pro čtení [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Vrací:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Vrací formát úseku. Pouze pro čtení [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Vrací:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


Kopíruje formát textu do zadaného textového rámce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textový rámec, do kterého se má formát textu zkopírovat. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Kopíruje formát textu ze zadaného textového rámce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Textový rámec, ze kterého se má formát textu zkopírovat. |