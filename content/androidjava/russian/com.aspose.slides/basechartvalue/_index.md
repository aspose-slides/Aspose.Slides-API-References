---
title: BaseChartValue
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет значение диаграммы.
type: docs
url: /ru/com.aspose.slides/basechartvalue/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Представляет значение диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Указывает, является ли свойство AsCell, AsCells, AsLiteralString или AsLiteralDouble актуальным в наследниках. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Указывает, является ли свойство AsCell, AsCells, AsLiteralString или AsLiteralDouble актуальным в наследниках. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Указывает, является ли свойство AsCell, AsCells, AsLiteralString или AsLiteralDouble актуальным в наследниках. Иными словами, указывает тип значения свойства Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Для точек в ChartDataPointCollection это свойство только для чтения. В этом случае для изменения значения этого свойства можно использовать одно из свойств ChartDataPointCollection.DataSourceTypeFor<...>.

**Возвращаемое значение:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Указывает, является ли свойство AsCell, AsCells, AsLiteralString или AsLiteralDouble актуальным в наследниках. Иными словами, указывает тип значения свойства Data. Чтение/запись [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Для точек в ChartDataPointCollection это свойство только для чтения. В этом случае для изменения значения этого свойства можно использовать одно из свойств ChartDataPointCollection.DataSourceTypeFor<...>.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getData() {#getData--}
```
public abstract Object getData()
```

Data. Чтение/запись Object.

**Возвращаемое значение:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Data. Чтение/запись Object.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent\_Immediate. Только чтение IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject