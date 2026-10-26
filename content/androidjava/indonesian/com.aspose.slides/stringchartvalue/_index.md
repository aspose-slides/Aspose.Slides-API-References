---
title: StringChartValue
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili nilai string yang dapat disimpan dalam dokumen presentasi pptx dengan dua cara: 1) dalam sel/sel-sel workbook yang terkait dengan diagram; 2) sebagai nilai literal.
type: docs
url: /id/com.aspose.slides/stringchartvalue/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Mewakili nilai string yang dapat disimpan dalam dokumen presentasi pptx dengan dua cara: 1) dalam sel/sel-sel workbook yang terkait dengan diagram; 2) sebagai nilai literal.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAsCells()](#getAsCells--) | Penetapan nilai null tidak diizinkan. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Penetapan nilai null tidak diizinkan. |
| [getAsLiteralString()](#getAsLiteralString--) | Mengembalikan atau mengatur nilai sebagai string literal. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Mengembalikan atau mengatur nilai sebagai string literal. |
| [getData()](#getData--) | Mengembalikan atau mengatur objek Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Mengembalikan atau mengatur objek Data. |
| [toString()](#toString--) | Mengembalikan data nilai string. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Menetapkan nilai dari sel yang ditentukan. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Jika properti DataSourceType adalah DataSourceType.Worksheet maka metode ini mengembalikan alamat sel-sel dalam workbook yang mewakili data string. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Penetapan nilai null tidak diizinkan. Nilai yang dikembalikan selalu tidak null. Baca/tulis [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Mengembalikan:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Penetapan nilai null tidak diizinkan. Nilai yang dikembalikan selalu tidak null. Baca/tulis [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Mengembalikan atau mengatur nilai sebagai string literal. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Mengembalikan atau mengatur nilai sebagai string literal. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

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

### toString() {#toString--}
```
public String toString()
```

Mengembalikan data nilai string. Mengembalikan null jika DataSourceType false dan tidak ada nilai string yang ditetapkan.

**Mengembalikan:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Menetapkan nilai dari sel yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Sel. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Jika properti DataSourceType adalah DataSourceType.Worksheet maka metode ini mengembalikan alamat sel-sel dalam workbook yang mewakili data string. Jika tidak, mengembalikan string kosong.

**Mengembalikan:**
java.lang.String