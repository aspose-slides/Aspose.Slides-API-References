---
title: BaseChartValue
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili nilai dari sebuah grafik.
type: docs
url: /id/com.aspose.slides/basechartvalue/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Mewakili nilai dari sebuah grafik.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Menentukan apakah properti AsCell, AsCells, AsLiteralString atau AsLiteralDouble berlaku pada turunan. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Menentukan apakah properti AsCell, AsCells, AsLiteralString atau AsLiteralDouble berlaku pada turunan. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Menentukan apakah properti AsCell, AsCells, AsLiteralString atau AsLiteralDouble berlaku pada turunan. Dengan kata lain, ini menentukan tipe nilai dari properti Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Untuk titik-titik dalam ChartDataPointCollection properti ini hanya dapat dibaca. Dalam hal ini, untuk mengubah nilai properti ini Anda dapat menggunakan salah satu properti ChartDataPointCollection.DataSourceTypeFor<...>.

**Mengembalikan:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Menentukan apakah properti AsCell, AsCells, AsLiteralString atau AsLiteralDouble berlaku pada turunan. Dengan kata lain, ini menentukan tipe nilai dari properti Data. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Untuk titik-titik dalam ChartDataPointCollection properti ini hanya dapat dibaca. Dalam hal ini, untuk mengubah nilai properti ini Anda dapat menggunakan salah satu properti ChartDataPointCollection.DataSourceTypeFor<...>.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Data. Baca/tulis Object.

**Mengembalikan:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Data. Baca/tulis Object.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject