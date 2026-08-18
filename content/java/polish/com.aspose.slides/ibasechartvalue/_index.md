---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje wartość wykresu.
type: docs
url: /pl/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Reprezentuje wartość wykresu.
## Metody

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Określa, czy właściwość AsCell, AsLiteralString lub AsLiteralDouble jest aktualna. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Określa, czy właściwość AsCell, AsLiteralString lub AsLiteralDouble jest aktualna. |
| [getData()](#getData--) | Odczyt/zapis Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Odczyt/zapis Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Określa, czy właściwość AsCell, AsLiteralString lub AsLiteralDouble jest aktualna. Innymi słowy określa typ wartości właściwości Data. Ta właściwość jest tylko do odczytu. Aby zmienić wartość tej właściwości, możesz użyć jednej z właściwości ChartDataPointCollection.DataSourceTypeFor<...>. Odczyt/zapis [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Zwraca:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```


Określa, czy właściwość AsCell, AsLiteralString lub AsLiteralDouble jest aktualna. Innymi słowy określa typ wartości właściwości Data. Ta właściwość jest tylko do odczytu. Aby zmienić wartość tej właściwości, możesz użyć jednej z właściwości ChartDataPointCollection.DataSourceTypeFor<...>. Odczyt/zapis [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```


Odczyt/zapis Object.

**Zwraca:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```


Odczyt/zapis Object.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |