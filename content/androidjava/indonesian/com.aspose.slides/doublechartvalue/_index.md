---
title: DoubleChartValue
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili nilai double yang dapat disimpan dalam dokumen presentasi pptx dengan dua cara: 1) di sel/sel workbook yang terkait dengan grafik; 2) sebagai nilai literal.
type: docs
url: /id/com.aspose.slides/doublechartvalue/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Mewakili nilai double yang dapat disimpan dalam dokumen presentasi pptx dengan dua cara: 1) di sel/sel workbook yang berhubungan dengan grafik; 2) sebagai nilai literal.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAsCell()](#getAsCell--) | Mengembalikan atau mengatur sel data grafik. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Mengembalikan atau mengatur sel data grafik. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Mengembalikan atau mengatur nilai sebagai double literal. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Mengembalikan atau mengatur nilai sebagai double literal. |
| [getData()](#getData--) | Mengembalikan atau mengatur objek Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Mengembalikan atau mengatur objek Data. |
| [toDouble()](#toDouble--) | Mengonversi ke double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Mengembalikan atau mengatur sel data grafik. Baca/tulis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Mengembalikan atau mengatur sel data grafik. Baca/tulis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Mengembalikan atau mengatur nilai sebagai double literal. Baca/tulis double.

**Mengembalikan:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Mengembalikan atau mengatur nilai sebagai double literal. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

Mengembalikan atau mengatur objek Data. Baca/tulis Object.

**Mengembalikan:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Mengembalikan atau mengatur objek Data. Baca/tulis Object.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

Mengonversi ke double.

**Mengembalikan:**
double - Mengembalikan LiteralDouble jika DataSourceType sama dengan DoubleLiterals. Jika DataSourceType sama dengan Worksheet mengembalikan nilai sel yang berhasil dikonversi ke double, selain itu mengembalikan NaN.