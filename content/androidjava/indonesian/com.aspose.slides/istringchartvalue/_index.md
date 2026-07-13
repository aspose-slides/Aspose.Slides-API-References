---
title: IStringChartValue
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili nilai string yang dapat disimpan dalam dokumen presentasi pptx dengan dua cara: 1) dalam sel/sel workbook yang terkait dengan diagram; 2) sebagai nilai literal.
type: docs
url: /id/com.aspose.slides/istringchartvalue/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Mewakili nilai string yang dapat disimpan dalam dokumen presentasi pptx dengan dua cara: 1) dalam sel/sel-sel workbook yang terkait dengan diagram; 2) sebagai nilai literal.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Mengembalikan atau mengatur string literal jika properti DataSourceType adalah DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Mengembalikan atau mengatur string literal jika properti DataSourceType adalah DataSourceType.StringLiterals. |
| [toString()](#toString--) | Mengembalikan representasi string. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Mengatur nilai dari sel yang ditentukan. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Jika properti DataSourceType adalah DataSourceType.Worksheet maka metode ini mengembalikan alamat sel-sel dalam workbook yang mewakili data string. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Mengembalikan atau mengatur string literal jika properti DataSourceType adalah DataSourceType.StringLiterals. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Mengembalikan atau mengatur string literal jika properti DataSourceType adalah DataSourceType.StringLiterals. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Mengembalikan representasi string.

**Mengembalikan:**
java.lang.String - Representasi string dari nilai String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Mengatur nilai dari sel yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Jika properti DataSourceType adalah DataSourceType.Worksheet maka metode ini mengembalikan alamat sel-sel dalam workbook yang mewakili data string. Jika tidak, mengembalikan string kosong.

**Mengembalikan:**
java.lang.String - Nilai string String