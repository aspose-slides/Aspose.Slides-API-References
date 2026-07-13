---
title: IBaseChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili nilai dari sebuah diagram.
type: docs
url: /id/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Mewakili nilai dari sebuah diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual. |
| [getData()](#getData--) | Baca/tulis Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Baca/tulis Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual. Dengan kata lain ini menentukan tipe nilai dari properti Data. Properti ini hanya-baca. Untuk mengubah nilai properti ini, Anda dapat menggunakan salah satu properti ChartDataPointCollection.DataSourceTypeFor<...>. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Mengembalikan:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

Menentukan apakah properti AsCell atau AsLiteralString atau AsLiteralDouble yang aktual. Dengan kata lain ini menentukan tipe nilai dari properti Data. Properti ini hanya-baca. Untuk mengubah nilai properti ini, Anda dapat menggunakan salah satu properti ChartDataPointCollection.DataSourceTypeFor<...>. Baca/tulis [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

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