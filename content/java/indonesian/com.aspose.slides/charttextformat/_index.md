---
title: ChartTextFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan format teks default untuk elemen teks diagram.
type: docs
url: /id/com.aspose.slides/charttextformat/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Menentukan format teks default untuk elemen teks diagram.
## Metode

| Method | Description |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copies text format to specified text frame. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copies text format from specified text frame. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Hanya-baca [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Mengembalikan:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Hanya-baca [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Mengembalikan:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Hanya-baca [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Mengembalikan:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Menyalin format teks ke bingkai teks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Bingkai teks untuk menyalin format teks ke. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Menyalin format teks dari bingkai teks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Bingkai teks untuk menyalin format teks. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject