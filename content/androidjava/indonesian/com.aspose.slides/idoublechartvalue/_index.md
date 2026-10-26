---
title: IDoubleChartValue
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili nilai double yang dapat disimpan dalam dokumen presentasi pptx dengan dua cara 1 dalam sel/sel-sel workbook yang terkait dengan chart 2 sebagai nilai literal.
type: docs
url: /id/com.aspose.slides/idoublechartvalue/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Mewakili nilai double yang dapat disimpan dalam dokumen presentasi pptx dengan dua cara: 1) dalam sel/sel-sel workbook yang terkait dengan chart; 2) sebagai nilai literal.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Mengembalikan atau mengatur nilai double literal jika DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Mengembalikan atau mengatur nilai double literal jika DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Mengonversi ke double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


Mengembalikan atau mengatur nilai double literal jika DataSourceType = Charts.DataSourceType.DoubleLiterals. Baca/tulis double.

**Mengembalikan:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


Mengembalikan atau mengatur nilai double literal jika DataSourceType = Charts.DataSourceType.DoubleLiterals. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Mengonversi ke double.

**Mengembalikan:**
double - Nilai double.