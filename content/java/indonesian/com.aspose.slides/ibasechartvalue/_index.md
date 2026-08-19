---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a value of a chart.
type: docs
url: /id/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Mewakili nilai dari sebuah diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya. |
| [getData()](#getData--) | Baca/tulis Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Baca/tulis Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya. Dengan kata lain, ini menentukan tipe nilai dari properti Data. Properti ini bersifat baca-saja. Untuk mengubah nilai properti ini, Anda dapat menggunakan salah satu properti ChartDataPointCollection.DataSourceTypeFor<...>. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Mengembalikan:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang sebenarnya. Dengan kata lain, ini menentukan tipe nilai dari properti Data. Properti ini bersifat baca-saja. Untuk mengubah nilai properti ini, Anda dapat menggunakan salah satu properti ChartDataPointCollection.DataSourceTypeFor<...>. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Baca/tulis Object.

**Mengembalikan:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Baca/tulis Object.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |