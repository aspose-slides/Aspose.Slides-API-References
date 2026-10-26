---
title: Trendline
second_title: Aspose.Slides для Android через справочник Java API
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
| [getTrendlineName()](#getTrendlineName--) | Получает или задаёт имя линии тренда. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Получает или задаёт имя линии тренда. |
| [getTrendlineType()](#getTrendlineType--) | Получает или задаёт тип линии тренда. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Получает или задаёт тип линии тренда. |
| [getFormat()](#getFormat--) | Представляет формат линии тренда. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Представляет формат линии тренда. |
| [getBackward()](#getBackward--) | Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда вытягивается до данных серии, которые тренируются. |
| [setBackward(double value)](#setBackward-double-) | Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда вытягивается до данных серии, которые тренируются. |
| [getForward()](#getForward--) | Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда вытягивается после данных серии, которые тренируются. |
| [setForward(double value)](#setForward-double-) | Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда вытягивается после данных серии, которые тренируются. |
| [getIntercept()](#getIntercept--) | Указывает значение, где линия тренда пересекает ось Y. |
| [setIntercept(double value)](#setIntercept-double-) | Указывает значение, где линия тренда пересекает ось Y. |
| [getDisplayEquation()](#getDisplayEquation--) | Указывает, что уравнение линии тренда отображается на диаграмме (в той же подписи, что и значение R-квадрат). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Указывает, что уравнение линии тренда отображается на диаграмме (в той же подписи, что и значение R-квадрат). |
| [getOrder()](#getOrder--) | Указывает порядок полиномиальной линии тренда. |
| [setOrder(byte value)](#setOrder-byte-) | Указывает порядок полиномиальной линии тренда. |
| [getPeriod()](#getPeriod--) | Указывает период линии тренда для скользящей средней. |
| [setPeriod(byte value)](#setPeriod-byte-) | Указывает период линии тренда для скользящей средней. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Указывает, что значение R-квадрат линии тренда отображается на диаграмме (в той же подписи, что и уравнение). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Указывает, что значение R-квадрат линии тренда отображается на диаграмме (в той же подписи, что и уравнение). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Представляет запись легенды, связанную с этой линией тренда. Только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Инициализировать TextFrameForOverriding текстом из параметра "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Может содержать текст с богатым форматированием. |
| [getTextFormat()](#getTextFormat--) | Возвращает формат текста. |
| [getChart()](#getChart--) | Возвращает родительскую диаграмму. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд FillFormat. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию FillFormat. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Получает или задаёт имя линии тренда. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Получает или задаёт имя линии тренда. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Получает или задаёт тип линии тренда. Чтение/запись [TrendlineType](../../com.aspose.slides/trendlinetype).

**Возвращаемое значение:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Получает или задаёт тип линии тренда. Чтение/запись [TrendlineType](../../com.aspose.slides/trendlinetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Представляет формат линии тренда. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Возвращаемое значение:**
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

Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда вытягивается до данных серии, которые тренируются. На диаграммах рассеяния и остальных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Возвращаемое значение:**
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда вытягивается до данных серии, которые тренируются. На диаграммах рассеяния и остальных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда вытягивается после данных серии, которые тренируются. На диаграммах рассеяния и остальных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Возвращаемое значение:**
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Указывает количество категорий (или единиц на диаграмме рассеяния), на которое линия тренда вытягивается после данных серии, которые тренируются. На диаграммах рассеяния и остальных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Указывает значение, где линия тренда пересекает ось Y. Это свойство поддерживается только для типов тренда exp, linear или poly. Чтение/запись double.

**Возвращаемое значение:**
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

**Возвращаемое значение:**
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

**Возвращаемое значение:**
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

Указывает период линии тренда для скользящей средней. Игнорируется для других вариантов линий тренда. Значение должно быть от 2 до 255. Чтение/запись byte.

**Возвращаемое значение:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Указывает период линии тренда для скользящей средней. Игнорируется для других вариантов линий тренда. Значение должно быть от 2 до 255. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Указывает, что значение R-квадрат линии тренда отображается на диаграмме (в той же подписи, что и уравнение). Чтение/запись boolean.

**Возвращаемое значение:**
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

**Возвращаемое значение:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Инициализировать TextFrameForOverriding текстом из параметра "text". Если TextFrameForOverriding уже инициализирован, просто изменяется его текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для нового TextFrameForOverriding. |

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Может содержать текст с богатым форматированием. Если это свойство не равно null, то его значение переопределяет автоматически сгенерированный текст метки данных. Автоматически сгенерированный текст метки данных — это текст, управляемый свойствами ShowSeriesName, ShowValue и т.п., и форматированный свойством TextFormatManager.TextFormat. Только для чтения [ITextFrame](../../com.aspose.slides/itextframe).

**Возвращаемое значение:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Возвращает формат текста. Только для чтения [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Возвращаемое значение:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Возвращает родительскую диаграмму. Только для чтения [IChart](../../com.aspose.slides/ichart).

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд FillFormat. Только для чтения [BaseSlide](../../com.aspose.slides/baseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию FillFormat. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)