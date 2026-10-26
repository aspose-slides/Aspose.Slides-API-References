---
title: ITrendline
second_title: Aspose.Slides для Android через справочник Java API
description: Класс представляет трендовую линию серии диаграммы
type: docs
url: /ru/com.aspose.slides/itrendline/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Класс представляет трендовую линию серии диаграммы
## Методы

| Метод | Описание |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Получает или задает имя трендовой линии. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Получает или задает имя трендовой линии. |
| [getTrendlineType()](#getTrendlineType--) | Получает или задает тип трендовой линии. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Получает или задает тип трендовой линии. |
| [getFormat()](#getFormat--) | Представляет формат трендовой линии. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Представляет формат трендовой линии. |
| [getBackward()](#getBackward--) | Указывает количество категорий (или единиц на диаграмме разброса), на которое трендовая линия простирается до данных для серии, для которой построен тренд. |
| [setBackward(double value)](#setBackward-double-) | Указывает количество категорий (или единиц на диаграмме разброса), на которое трендовая линия простирается до данных для серии, для которой построен тренд. |
| [getForward()](#getForward--) | Указывает количество категорий (или единиц на диаграмме разброса), на которое трендовая линия простирается после данных для серии, для которой построен тренд. |
| [setForward(double value)](#setForward-double-) | Указывает количество категорий (или единиц на диаграмме разброса), на которое трендовая линия простирается после данных для серии, для которой построен тренд. |
| [getIntercept()](#getIntercept--) | Указывает значение, в котором трендовая линия пересекает ось Y. |
| [setIntercept(double value)](#setIntercept-double-) | Указывает значение, в котором трендовая линия пересекает ось Y. |
| [getDisplayEquation()](#getDisplayEquation--) | Указывает, что уравнение для трендовой линии отображается на диаграмме (в той же метке, что и Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Указывает, что уравнение для трендовой линии отображается на диаграмме (в той же метке, что и Rsquaredvalue). |
| [getOrder()](#getOrder--) | Указывает порядок полиномиальной трендовой линии. |
| [setOrder(byte value)](#setOrder-byte-) | Указывает порядок полиномиальной трендовой линии. |
| [getPeriod()](#getPeriod--) | Указывает период трендовой линии для скользящей средней. |
| [setPeriod(byte value)](#setPeriod-byte-) | Указывает период трендовой линии для скользящей средней. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Указывает, что значение R-squared трендовой линии отображается на диаграмме (в той же метке, что и уравнение). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Указывает, что значение R-squared трендовой линии отображается на диаграмме (в той же метке, что и уравнение). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Представляет элемент легенды, связанный с этой трендовой линией, только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```


Получает или задает имя трендовой линии. Чтение/запись String.

**Возвращает:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```


Получает или задает имя трендовой линии. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```


Получает или задает тип трендовой линии. Чтение/запись [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Возвращает:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```


Получает или задает тип трендовой линии. Чтение/запись [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Представляет формат трендовой линии. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Представляет формат трендовой линии. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```


Указывает количество категорий (или единиц на диаграмме разброса), на которое трендовая линия простирается до данных для серии, для которой построен тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Возвращает:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```


Указывает количество категорий (или единиц на диаграмме разброса), на которое трендовая линия простирается до данных для серии, для которой построен тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```


Указывает количество категорий (или единиц на диаграмме разброса), на которое трендовая линия простирается после данных для серии, для которой построен тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Возвращает:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```


Указывает количество категорий (или единиц на диаграмме разброса), на которое трендовая линия простирается после данных для серии, для которой построен тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```


Указывает значение, в котором трендовая линия пересекает ось Y. Это свойство поддерживается только при типе трендовой линии exp, linear или poly. Чтение/запись double.

**Возвращает:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```


Указывает значение, в котором трендовая линия пересекает ось Y. Это свойство поддерживается только при типе трендовой линии exp, linear или poly. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```


Указывает, что уравнение для трендовой линии отображается на диаграмме (в той же метке, что и Rsquaredvalue). Чтение/запись boolean.

**Возвращает:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```


Указывает, что уравнение для трендовой линии отображается на диаграмме (в той же метке, что и Rsquaredvalue). Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```


Указывает порядок полиномиальной трендовой линии. Игнорируется для других типов трендовых линий. Значение должно быть от 2 до 6. Чтение/запись byte.

**Возвращает:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```


Указывает порядок полиномиальной трендовой линии. Игнорируется для других типов трендовых линий. Значение должно быть от 2 до 6. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```


Указывает период трендовой линии для скользящей средней. Игнорируется для других вариантов трендовых линий. Значение должно быть от 2 до 255. Чтение/запись byte.

**Возвращает:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```


Указывает период трендовой линии для скользящей средней. Игнорируется для других вариантов трендовых линий. Значение должно быть от 2 до 255. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```


Указывает, что значение R-squared трендовой линии отображается на диаграмме (в той же метке, что и уравнение). Чтение/запись boolean.

**Возвращает:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```


Указывает, что значение R-squared трендовой линии отображается на диаграмме (в той же метке, что и уравнение). Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Представляет элемент легенды, связанный с этой трендовой линией, только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Возвращает:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)