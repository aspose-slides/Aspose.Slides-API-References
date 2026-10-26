---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Java API Reference
description: Указывает значения линий погрешности.
type: docs
url: /ru/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Указывает значения линий погрешности. Должен использоваться только когда тип значения линий погрешности равен Custom.
## Методы

| Метод | Описание |
| --- | --- |
| [getXMinus()](#getXMinus--) | Указывает значение линии погрешности в отрицательном направлении. |
| [getYMinus()](#getYMinus--) | Указывает значение линии погрешности в отрицательном направлении. |
| [getXPlus()](#getXPlus--) | Указывает значение линии погрешности в положительном направлении. |
| [getYPlus()](#getYPlus--) | Указывает значение линии погрешности в положительном направлении. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```


Указывает значение линии погрешности в отрицательном направлении. Доступно, если тип значения линий погрешности равен Custom и ErrorBarsXFormat разрешён. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```


Указывает значение линии погрешности в отрицательном направлении. Доступно, если тип значения линий погрешности равен Custom и ErrorBarsYFormat разрешён. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```


Указывает значение линии погрешности в положительном направлении. Доступно, если тип значения линий погрешности равен Custom и ErrorBarsXFormat разрешён. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```


Указывает значение линии погрешности в положительном направлении. Доступно, если тип значения линий погрешности равен Custom и ErrorBarsYFormat разрешён. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)