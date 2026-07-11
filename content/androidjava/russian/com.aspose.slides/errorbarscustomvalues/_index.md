---
title: ErrorBarsCustomValues
second_title: Aspose.Slides для Android через справочник Java API
description: Указывает значения полос ошибок.
type: docs
url: /ru/com.aspose.slides/errorbarscustomvalues/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
```
public class ErrorBarsCustomValues extends DomObject<ChartDataPoint> implements IErrorBarsCustomValues
```

Указывает значения Error bars. Должна использоваться только когда тип значения Error bars равен Custom.
## Методы

| Метод | Описание |
| --- | --- |
| [getXMinus()](#getXMinus--) | Указывает значение error bar в отрицательном направлении. |
| [getYMinus()](#getYMinus--) | Указывает значение error bar в отрицательном направлении. |
| [getXPlus()](#getXPlus--) | Указывает значение error bar в положительном направлении. |
| [getYPlus()](#getYPlus--) | Указывает значение error bar в положительном направлении. |
### getXMinus() {#getXMinus--}
```
public final IDoubleChartValue getXMinus()
```

Указывает значение error bar в отрицательном направлении. Доступно, если тип значения error bars равен Custom и разрешён ErrorBarsXFormat. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращает:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public final IDoubleChartValue getYMinus()
```

Указывает значение error bar в отрицательном направлении. Доступно, если тип значения error bars равен Custom и разрешён ErrorBarsYFormat. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращает:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public final IDoubleChartValue getXPlus()
```

Указывает значение error bar в положительном направлении. Доступно, если тип значения error bars равен Custom и разрешён ErrorBarsXFormat. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращает:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public final IDoubleChartValue getYPlus()
```

Указывает значение error bar в положительном направлении. Доступно, если тип значения error bars равен Custom и разрешён ErrorBarsYFormat. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращает:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)