---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Diagram beroperasi dengan satu set terbatas properti format teks.
type: docs
url: /id/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Diagram beroperasi dengan satu set terbatas properti format teks. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat antarmuka menjelaskan set terbatas ini.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Mengembalikan format untuk elemen teks diagram. |
| [getParagraphFormat()](#getParagraphFormat--) | Mengembalikan format paragraf. |
| [getPortionFormat()](#getPortionFormat--) | Mengembalikan format bagian. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Menyalin format teks ke kerangka teks yang ditentukan. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Menyalin format teks dari kerangka teks yang ditentukan. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


Mengembalikan format untuk elemen teks diagram. Baca-saja [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Mengembalikan:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Mengembalikan format paragraf. Baca-saja [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Mengembalikan:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Mengembalikan format bagian. Baca-saja [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Mengembalikan:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


Menyalin format teks ke kerangka teks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Kerangka teks untuk menyalin format teks ke. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


Menyalin format teks dari kerangka teks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Kerangka teks untuk menyalin format teks. |