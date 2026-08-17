---
title: IErrorBarsFormat
second_title: Справочник API Aspose.Slides для Java
description: Представляет полосы ошибок серии диаграммы.
type: docs
url: /ru/com.aspose.slides/ierrorbarsformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection (in [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) property).

## Методы

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Получает или задает тип полос ошибок. |
| [setType(int value)](#setType-int-) | Получает или задает тип полос ошибок. |
| [getValueType()](#getValueType--) | Представляет возможные способы определения длины полос ошибок. |
| [setValueType(int value)](#setValueType-int-) | Представляет возможные способы определения длины полос ошибок. |
| [hasEndCap()](#hasEndCap--) | Указывает, что конец не рисуется на полосах ошибок. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Указывает, что конец не рисуется на полосах ошибок. |
| [getValue()](#getValue--) | Получает или задает значение, используемое с типами значений Fixed, Percentage и StandardDeviation для определения длины полос ошибок. |
| [setValue(float value)](#setValue-float-) | Получает или задает значение, используемое с типами значений Fixed, Percentage и StandardDeviation для определения длины полос ошибок. |
| [getFormat()](#getFormat--) | Представляет формат полос ошибок. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Представляет формат полос ошибок. |
| [isVisible()](#isVisible--) | Получает или задает видимость Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | Получает или задает видимость Error Bars. |
### getType() {#getType--}
```
public abstract int getType()
```

Получает или задает тип полос ошибок. Read/write [ErrorBarType](../../com.aspose.slides/errorbartype).

**Возвращаемое значение:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Получает или задает тип полос ошибок. Read/write [ErrorBarType](../../com.aspose.slides/errorbartype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Представляет возможные способы определения длины полос ошибок. In case of custom value type to specify value use [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. Read/write [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Возвращаемое значение:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Представляет возможные способы определения длины полос ошибок. In case of custom value type to specify value use [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) property of specific data point in DataPoints collection of series. Read/write [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Указывает, что конец не рисуется на полосах ошибок. Read/write boolean.

**Возвращаемое значение:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Указывает, что конец не рисуется на полосах ошибок. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Получает или задает значение, используемое с типами значений Fixed, Percentage и StandardDeviation для определения длины полос ошибок. Read/write float.

**Возвращаемое значение:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Получает или задает значение, используемое с типами значений Fixed, Percentage и StandardDeviation для определения длины полос ошибок. Read/write float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Представляет формат полос ошибок. Read/write [IFormat](../../com.aspose.slides/iformat).

**Возвращаемое значение:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Представляет формат полос ошибок. Read/write [IFormat](../../com.aspose.slides/iformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Получает или задает видимость Error Bars. Read/write boolean.

**Возвращаемое значение:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Получает или задает видимость Error Bars. Read/write boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |