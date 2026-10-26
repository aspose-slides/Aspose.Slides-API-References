---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Представляет значение диаграммы.
type: docs
url: /ru/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

Представляет значение диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Указывает, является ли AsCell или AsLiteralString или AsLiteralDouble свойство актуальным. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Указывает, является ли AsCell или AsLiteralString или AsLiteralDouble свойство актуальным. |
| [getData()](#getData--) | Чтение/запись Object. |
| [setData(Object value)](#setData-java.lang.Object-) | Чтение/запись Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Указывает, является ли AsCell или AsLiteralString или AsLiteralDouble свойство актуальным. Другими словами, указывает тип значения свойства Data. Это свойство только для чтения. Для изменения значения этого свойства можно использовать одно из свойств ChartDataPointCollection.DataSourceTypeFor<...>. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Возвращаемое значение:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

Указывает, является ли AsCell или AsLiteralString или AsLiteralDouble свойство актуальным. Другими словами, указывает тип значения свойства Data. Это свойство только для чтения. Для изменения значения этого свойства можно использовать одно из свойств ChartDataPointCollection.DataSourceTypeFor<...>. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```

Чтение/запись Object.

**Возвращаемое значение:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Чтение/запись Object.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  