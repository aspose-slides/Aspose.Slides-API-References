---
title: IErrorBarsCustomValues
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies the errors bar values.
type: docs
url: /ru/com.aspose.slides/ierrorbarscustomvalues/
---```
public interface IErrorBarsCustomValues
```

Указывает значения линии ошибок. Должен использоваться только когда тип значения линий ошибок — Custom.
## Методы

| Метод | Описание |
| --- | --- |
| [getXMinus()](#getXMinus--) | Указывает значение линии ошибок в отрицательном направлении. |
| [getYMinus()](#getYMinus--) | Указывает значение линии ошибок в отрицательном направлении. |
| [getXPlus()](#getXPlus--) | Указывает значение линии ошибок в положительном направлении. |
| [getYPlus()](#getYPlus--) | Указывает значение линии ошибок в положительном направлении. |
### getXMinus() {#getXMinus--}
```
public abstract IDoubleChartValue getXMinus()
```

Указывает значение линии ошибок в отрицательном направлении. Доступно, если тип значения линий ошибок — Custom и разрешён ErrorBarsXFormat. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYMinus() {#getYMinus--}
```
public abstract IDoubleChartValue getYMinus()
```

Указывает значение линии ошибок в отрицательном направлении. Доступно, если тип значения линий ошибок — Custom и разрешён ErrorBarsYFormat. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getXPlus() {#getXPlus--}
```
public abstract IDoubleChartValue getXPlus()
```

Указывает значение линии ошибок в положительном направлении. Доступно, если тип значения линий ошибок — Custom и разрешён ErrorBarsXFormat. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getYPlus() {#getYPlus--}
```
public abstract IDoubleChartValue getYPlus()
```

Указывает значение линии ошибок в положительном направлении. Доступно, если тип значения линий ошибок — Custom и разрешён ErrorBarsYFormat. В остальных случаях это свойство возвращает null. Только для чтения [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Возвращаемое значение:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)