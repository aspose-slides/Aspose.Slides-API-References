---
title: Trendline
second_title: Aspose.Slides для Java API Reference
description: Класс представляет линию тренда серии диаграммы
type: docs
url: /ru/com.aspose.slides/trendline/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Класс представляет линию тренда серии диаграммы
## Методы

| Метод | Описание |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Получает или задает имя линии тренда. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Получает или задает имя линии тренда. |
| [getTrendlineType()](#getTrendlineType--) | Получает или задает тип линии тренда. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Получает или задает тип линии тренда. |
| [getFormat()](#getFormat--) | Представляет формат линии тренда. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Представляет формат линии тренда. |
| [getBackward()](#getBackward--) | Указывает количество категорий (или единиц на точечной диаграмме), на которое линия тренда простирается до данных серии, для которой построен тренд. |
| [setBackward(double value)](#setBackward-double-) | Указывает количество категорий (или единиц на точечной диаграмме), на которое линия тренда простирается до данных серии, для которой построен тренд. |
| [getForward()](#getForward--) | Указывает количество категорий (или единиц на точечной диаграмме), на которое линия тренда простирается после данных серии, для которой построен тренд. |
| [setForward(double value)](#setForward-double-) | Указывает количество категорий (или единиц на точечной диаграмме), на которое линия тренда простирается после данных серии, для которой построен тренд. |
| [getIntercept()](#getIntercept--) | Указывает значение, где линия тренда пересекает ось Y. |
| [setIntercept(double value)](#setIntercept-double-) | Указывает значение, где линия тренда пересекает ось Y. |
| [getDisplayEquation()](#getDisplayEquation--) | Указывает, что уравнение линии тренда отображается на диаграмме (в той же подписи, что и значение R-квадрат). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Указывает, что уравнение линии тренда отображается на диаграмме (в той же подписи, что и значение R-квадрат). |
| [getOrder()](#getOrder--) | Указывает порядок полиномиальной линии тренда. |
| [setOrder(byte value)](#setOrder-byte-) | Указывает порядок полиномиальной линии тренда. |
| [getPeriod()](#getPeriod--) | Указывает период линии тренда для линии скользящего среднего. |
| [setPeriod(byte value)](#setPeriod-byte-) | Указывает период линии тренда для линии скользящего среднего. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Указывает, что значение R-квадрат линии тренда отображается на диаграмме (в той же подписи, что и уравнение). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Указывает, что значение R-квадрат линии тренда отображается на диаграмме (в той же подписи, что и уравнение). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Представляет запись легенды, связанную с этой линией тренда. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Инициализирует TextFrameForOverriding текстом из параметра "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Может содержать текст с богатым форматированием. |
| [getTextFormat()](#getTextFormat--) | Возвращает формат текста. |
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [getSlide()](#getSlide--) | Возвращает слайд-родитель FillFormat. |
| [getPresentation()](#getPresentation--) | Возвращает презентацию-родитель FillFormat. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Получает или задает имя линии тренда. Чтение/запись String.

**Возвращает:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Получает или задает имя линии тренда. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Получает или задает тип линии тренда. Чтение/запись [TrendlineType](../../com.aspose.slides/trendlinetype).

**Возвращает:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Получает или задает тип линии тренда. Чтение/запись [TrendlineType](../../com.aspose.slides/trendlinetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Представляет формат линии тренда. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Представляет формат линии тренда. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

Указывает количество категорий (или единиц на точечной диаграмме), на которое линия тренда простирается до данных серии, для которой построен тренд. На точечных и не точечных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Возвращает:**
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Указывает количество категорий (или единиц на точечной диаграмме), на которое линия тренда простирается до данных серии, для которой построен тренд. На точечных и не точечных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

Указывает количество категорий (или единиц на точечной диаграмме), на которое линия тренда простирается после данных серии, для которой построен тренд. На точечных и не точечных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Возвращает:**
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Указывает количество категорий (или единиц на точечной диаграмме), на которое линия тренда простирается после данных серии, для которой построен тренд. На точечных и не точечных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Указывает значение, где линия тренда пересекает ось Y. Это свойство поддерживается только для типов тренда exp, linear или poly. Чтение/запись double.

**Возвращает:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Указывает значение, где линия тренда пересекает ось Y. Это свойство поддерживается только для типов тренда exp, linear или poly. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Указывает, что уравнение линии тренда отображается на диаграмме (в той же подписи, что и значение R-квадрат). Чтение/запись boolean.

**Возвращает:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Указывает, что уравнение линии тренда отображается на диаграмме (в той же подписи, что и значение R-квадрат). Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Указывает порядок полиномиальной линии тренда. Игнорируется для остальных типов линий тренда. Значение должно быть от 2 до 6. Чтение/запись byte.

**Возвращает:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Указывает порядок полиномиальной линии тренда. Игнорируется для остальных типов линий тренда. Значение должно быть от 2 до 6. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Указывает период линии тренда для линии скользящего среднего. Игнорируется для остальных вариантов линий тренда. Значение должно быть от 2 до 255. Чтение/запись byte.

**Возвращает:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Указывает период линии тренда для линии скользящего среднего. Игнорируется для остальных вариантов линий тренда. Значение должно быть от 2 до 255. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Указывает, что значение R-квадрат линии тренда отображается на диаграмме (в той же подписи, что и уравнение). Чтение/запись boolean.

**Возвращает:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Указывает, что значение R-квадрат линии тренда отображается на диаграмме (в той же подписи, что и уравнение). Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Представляет запись легенды, связанную с этой линией тренда. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Возвращает:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Инициализирует TextFrameForOverriding текстом из параметра "text". Если TextFrameForOverriding уже инициализирован, просто изменяет его текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для нового TextFrameForOverriding. |

**Возвращает:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Может содержать текст с богатым форматированием. Если это свойство не равно null, то отформатированный текст переопределяет автоматически сгенерированный текст метки данных. Автоматически сгенерированный текст метки данных — это текст, управляемый свойствами ShowSeriesName, ShowValue и т.д., и форматированный свойством TextFormatManager.TextFormat. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращает:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Возвращает формат текста. Только для чтения [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Возвращает:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает родительскую диаграмму. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возвращает:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает слайд-родитель FillFormat. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращает:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает презентацию-родитель FillFormat. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращает:**
[IPresentation](../../com.aspose.slides/ipresentation)