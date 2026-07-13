---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili nilai string atau double yang dapat disimpan dalam dokumen presentasi pptx dengan dua cara: 1) di sel/sel workbook yang terkait dengan diagram; 2) sebagai nilai literal.
type: docs
url: /id/com.aspose.slides/istringordoublechartvalue/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Mewakili nilai string atau double yang dapat disimpan dalam dokumen presentasi pptx dengan dua cara: 1) di sel/sel workbook yang terkait dengan diagram; 2) sebagai nilai literal.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Mengembalikan atau mengatur literal String jika properti DataSourceType adalah DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Mengembalikan atau mengatur literal String jika properti DataSourceType adalah DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Mengembalikan atau mengatur literal double jika properti DataSourceType adalah DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Mengembalikan atau mengatur literal double jika properti DataSourceType adalah DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Mengonversi nilai ke double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Mengembalikan atau mengatur literal String jika properti DataSourceType adalah DataSourceType.StringLiterals. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Mengembalikan atau mengatur literal String jika properti DataSourceType adalah DataSourceType.StringLiterals. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Mengembalikan atau mengatur literal double jika properti DataSourceType adalah DataSourceType.DoubleLiterals. Baca/tulis double.

**Mengembalikan:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Mengembalikan atau mengatur literal double jika properti DataSourceType adalah DataSourceType.DoubleLiterals. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Mengonversi nilai ke double.

**Mengembalikan:**
double - Double value double