---
title: IChartTextFormat
second_title: Aspose.Slides for Java API Reference
description: Chart operate with restricted set of text format properties.
type: docs
url: /pl/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Wykres działa z ograniczonym zestawem właściwości formatowania tekstu. Interfejsy IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat opisują ten ograniczony zestaw.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Zwraca format dla elementów tekstowych wykresu. |
| [getParagraphFormat()](#getParagraphFormat--) | Zwraca format akapitu. |
| [getPortionFormat()](#getPortionFormat--) | Zwraca format fragmentu. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopiuje format tekstu do określonej ramki tekstowej. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopiuje format tekstu z określonej ramki tekstowej. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Zwraca format dla elementów tekstowych wykresu. Tylko do odczytu [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Zwraca:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

Zwraca format akapitu. Tylko do odczytu [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Zwraca:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

Zwraca format fragmentu. Tylko do odczytu [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Zwraca:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

Kopiuje format tekstu do określonej ramki tekstowej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Ramka tekstowa, do której zostanie skopiowany format tekstu. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

Kopiuje format tekstu z określonej ramki tekstowej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Ramka tekstowa, z której zostanie skopiowany format tekstu. |