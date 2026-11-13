---
title: CachedChartValue
second_title: Справочник API Aspose.Slides для Java
description: Представляет кэшированное значение диаграммы, например X, Y, размер пузыря или основное значение.
type: docs
url: /ru/com.aspose.slides/cachedchartvalue/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Представляет кэшированное значение диаграммы (например, X, Y, размер пузыря или основное значение).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [toString()](#toString--) | Возвращает строковое представление кэшированного значения. |
| [toDouble()](#toDouble--) | Преобразует кэшированное значение в double. |
| [getData()](#getData--) | Получает объект кэшированных данных. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Возвращает строковое представление кэшированного значения.

**Возвращаемое значение:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Преобразует кэшированное значение в double.

**Возвращаемое значение:**
double - Численное представление, или Double.NaN если Data (#getData.getData/#setData(Object).setData(Object)) равно null или не может быть преобразовано в double.
### getData() {#getData--}
```
public final Object getData()
```


Получает объект кэшированных данных. Только для чтения Object .

**Возвращаемое значение:**
java.lang.Object