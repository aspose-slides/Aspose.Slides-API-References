---
title: ICachedChartValue
second_title: Aspose.Slides для Java API Reference
description: Представляет кэшированное значение диаграммы, например X, Y, размер пузыря или основное значение.
type: docs
url: /ru/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Представляет кэшированное значение диаграммы (например X, Y, размер пузыря или основное значение).
## Методы

| Метод | Описание |
| --- | --- |
| [getData()](#getData--) | Получает кэшированный объект данных. |
| [toDouble()](#toDouble--) | Преобразует кэшированное значение в тип double. |
### getData() {#getData--}
```
public abstract Object getData()
```


Получает кэшированный объект данных. Только для чтения  Object .

**Возвращает:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Преобразует кэшированное значение в тип double.

**Возвращает:**
double – числовое представление или Double.NaN, если Data (\#getData.getData) равно null или не может быть преобразовано в тип double.