---
title: ErrorBarsFormat
second_title: Aspose.Slides для Android через Java - справочник API
description: Представляет полосы ошибок серии диаграммы.
type: docs
url: /ru/com.aspose.slides/errorbarsformat/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Представляет полосы ошибок серии диаграммы. Пользовательские значения ErrorBars находятся в IChartDataPointCollection (в свойстве ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Получает или задает тип полос ошибок. |
| [setType(int value)](#setType-int-) | Получает или задает тип полос ошибок. |
| [getValueType()](#getValueType--) | Представляет возможные способы определения длины полос ошибок. |
| [setValueType(int value)](#setValueType-int-) | Представляет возможные способы определения длины полос ошибок. |
| [hasEndCap()](#hasEndCap--) | Указывает, что концевой колпачок не рисуется на полосах ошибок. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Указывает, что концевой колпачок не рисуется на полосах ошибок. |
| [getValue()](#getValue--) | Получает или задает значение, которое используется с типами Fixed, Percentage и StandardDeviation для определения длины полос ошибок. |
| [setValue(float value)](#setValue-float-) | Получает или задает значение, которое используется с типами Fixed, Percentage и StandardDeviation для определения длины полос ошибок. |
| [getFormat()](#getFormat--) | Представляет формат полос ошибок. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Представляет формат полос ошибок. |
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [isVisible()](#isVisible--) | Получает или задает видимость полос ошибок. |
| [setVisible(boolean value)](#setVisible-boolean-) | Получает или задает видимость полос ошибок. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд FillFormat. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию FillFormat. |
### getType() {#getType--}
```
public final int getType()
```

Получает или задает тип полос ошибок. Чтение/запись [ErrorBarType](../../com.aspose.slides/errorbartype).

**Возвращает:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Получает или задает тип полос ошибок. Чтение/запись [ErrorBarType](../../com.aspose.slides/errorbartype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Представляет возможные способы определения длины полос ошибок. В случае пользовательского типа значения для указания значения используйте свойство ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) конкретной точки данных в коллекции DataPoints серии. В случае типов значения Fixed, Percentage или StandardDeviation используйте свойство Value для указания значения. Чтение/запись [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Возвращает:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Представляет возможные способы определения длины полос ошибок. В случае пользовательского типа значения для указания значения используйте свойство ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) конкретной точки данных в коллекции DataPoints серии. В случае типов значения Fixed, Percentage или StandardDeviation используйте свойство Value для указания значения. Чтение/запись [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Указывает, что концевой колпачок не рисуется на полосах ошибок. Чтение/запись boolean.

**Возвращает:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Указывает, что концевой колпачок не рисуется на полосах ошибок. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Получает или задает значение, которое используется с типами Fixed, Percentage и StandardDeviation для определения длины полос ошибок. В любом другом случае вернёт NaN. Чтение/запись float.

**Возвращает:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Получает или задает значение, которое используется с типами Fixed, Percentage и StandardDeviation для определения длины полос ошибок. В любом другом случае вернёт NaN. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Представляет формат полос ошибок. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Представляет формат полос ошибок. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает родительскую диаграмму. Только чтение [IChart](../../com.aspose.slides/ichart).

**Возвращает:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Получает или задает видимость полос ошибок. Чтение/запись boolean.

**Возвращает:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Получает или задает видимость полос ошибок. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд FillFormat. Только чтение [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращает:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию FillFormat. Только чтение [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращает:**
[IPresentation](../../com.aspose.slides/ipresentation)