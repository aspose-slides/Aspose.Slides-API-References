---
title: IErrorBarsFormat
second_title: Справочник API Aspose.Slides для Android через Java
description: Представляет линии ошибок серии диаграммы.
type: docs
url: /ru/com.aspose.slides/ierrorbarsformat/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Представляет линии ошибок серии диаграммы. Пользовательские значения ErrorBars находятся в IChartDataPointCollection (в свойстве [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Gets or sets type of error bars. |
| [setType(int value)](#setType-int-) | Gets or sets type of error bars. |
| [getValueType()](#getValueType--) | Represents possible ways to determine the length of the error bars. |
| [setValueType(int value)](#setValueType-int-) | Represents possible ways to determine the length of the error bars. |
| [hasEndCap()](#hasEndCap--) | Specifies an end cap is not drawn on the error bars. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Specifies an end cap is not drawn on the error bars. |
| [getValue()](#getValue--) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [setValue(float value)](#setValue-float-) | Gets or sets value which is used with Fixed, Percentage and StandardDeviation value types to determine the length of the error bars. |
| [getFormat()](#getFormat--) | Represents the format of the error bars. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the format of the error bars. |
| [isVisible()](#isVisible--) | Gets or sets Error Bars visibility. |
| [setVisible(boolean value)](#setVisible-boolean-) | Gets or sets Error Bars visibility. |
### getType() {#getType--}
```
public abstract int getType()
```

Получает или задает тип линий ошибок. Чтение/запись [ErrorBarType](../../com.aspose.slides/errorbartype).

**Возвращаемое значение:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Получает или задает тип линий ошибок. Чтение/запись [ErrorBarType](../../com.aspose.slides/errorbartype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Представляет возможные способы определения длины линий ошибок. В случае пользовательского типа значения для указания значения используйте свойство [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) конкретной точки данных в коллекции DataPoints серии. Чтение/запись [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Возвращаемое значение:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Представляет возможные способы определения длины линий ошибок. В случае пользовательского типа значения для указания значения используйте свойство [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) конкретной точки данных в коллекции DataPoints серии. Чтение/запись [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Указывает, что на линиях ошибок не рисуется конечный колпачок. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Указывает, что на линиях ошибок не рисуется конечный колпачок. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Получает или задает значение, используемое с типами Fixed, Percentage и StandardDeviation для определения длины линий ошибок. Чтение/запись float.

**Возвращаемое значение:**
float
### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Получает или задает значение, используемое с типами Fixed, Percentage и StandardDeviation для определения длины линий ошибок. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Представляет формат линий ошибок. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Возвращаемое значение:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Представляет формат линий ошибок. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Получает или задает видимость линий ошибок. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Получает или задает видимость линий ошибок. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |