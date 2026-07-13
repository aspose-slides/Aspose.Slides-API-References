---
title: ChartTextFormat
second_title: Aspose.Slides dla Androida – odniesienie do API Java
description: Określa domyślne formatowanie tekstu dla elementów tekstowych wykresu.
type: docs
url: /pl/com.aspose.slides/charttextformat/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Określa domyślne formatowanie tekstu dla elementów tekstowych wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Kopiuje format tekstu do określonej ramki tekstowej. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Kopiuje format tekstu z określonej ramki tekstowej. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Tylko do odczytu [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Zwraca:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Tylko do odczytu [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Zwraca:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Tylko do odczytu [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Zwraca:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Kopiuje format tekstu do określonej ramki tekstowej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Ramka tekstowa, do której kopiowany jest format tekstu. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Kopiuje format tekstu z określonej ramki tekstowej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Ramka tekstowa, z której kopiowany jest format tekstu. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject