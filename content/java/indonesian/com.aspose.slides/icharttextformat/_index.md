---
title: IChartTextFormat
second_title: Aspose.Slides untuk Referensi API Java
description: Chart beroperasi dengan sekumpulan properti format teks yang terbatas.
type: docs
url: /id/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Chart beroperasi dengan sekumpulan properti format teks yang terbatas. Antarmuka IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat menjelaskan kumpulan terbatas ini.
## Metode

| Method | Description |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Returns format for the chart text elements. |
| [getParagraphFormat()](#getParagraphFormat--) | Returns paragraph format. |
| [getPortionFormat()](#getPortionFormat--) | Returns portion format. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copies text format to specified text frame. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copies text format from specified text frame. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Mengembalikan format untuk elemen teks chart. Hanya-baca [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Mengembalikan:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

Mengembalikan format paragraf. Hanya-baca [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Mengembalikan:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

Mengembalikan format bagian. Hanya-baca [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Mengembalikan:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

Menyalin format teks ke frame teks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Frame teks untuk menyalin format teks ke. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

Menyalin format teks dari frame teks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Frame teks untuk menyalin format teks. |