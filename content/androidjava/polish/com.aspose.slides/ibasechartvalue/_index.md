---
title: IBaseChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje wartość wykresu.
type: docs
url: /pl/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Reprezentuje wartość wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Określa, czy właściwość AsCell, AsLiteralString lub AsLiteralDouble jest aktualna. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Określa, czy właściwość AsCell, AsLiteralString lub AsLiteralDouble jest aktualna. |
| [getData()](#getData--) | Odczyt/zapis Obiekt. |
| [setData(Object value)](#setData-java.lang.Object-) | Odczyt/zapis Obiekt. |
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
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Odczyt/zapis Obiekt.

**Zwraca:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Odczyt/zapis Obiekt.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Object |  |