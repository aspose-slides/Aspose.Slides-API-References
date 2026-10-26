---
title: ITrendline
second_title: Справочник API Aspose.Slides для Java
description: Класс представляет линию тренда серии диаграммы
type: docs
url: /ru/com.aspose.slides/itrendline/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
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
| [getBackward()](#getBackward--) | Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается до данных серии, к которой применяется тренд. |
| [setBackward(double value)](#setBackward-double-) | Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается до данных серии, к которой применяется тренд. |
| [getForward()](#getForward--) | Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается после данных серии, к которой применяется тренд. |
| [setForward(double value)](#setForward-double-) | Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается после данных серии, к которой применяется тренд. |
| [getIntercept()](#getIntercept--) | Указывает значение, где линия тренда пересекает ось y. |
| [setIntercept(double value)](#setIntercept-double-) | Указывает значение, где линия тренда пересекает ось y. |
| [getDisplayEquation()](#getDisplayEquation--) | Указывает, что уравнение линии тренда отображается на диаграмме (в той же метке, что и Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Указывает, что уравнение линии тренда отображается на диаграмме (в той же метке, что и Rsquaredvalue). |
| [getOrder()](#getOrder--) | Указывает порядок полиномиальной линии тренда. |
| [setOrder(byte value)](#setOrder-byte-) | Указывает порядок полиномиальной линии тренда. |
| [getPeriod()](#getPeriod--) | Указывает период линии тренда для линии скользящего среднего. |
| [setPeriod(byte value)](#setPeriod-byte-) | Указывает период линии тренда для линии скользящего среднего. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Указывает, что значение R-squared линии тренда отображается на диаграмме (в той же метке, что и уравнение). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Указывает, что значение R-squared линии тренда отображается на диаграмме (в той же метке, что и уравнение). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Представляет элемент легенды, связанный с этой линией тренда, только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Получает или задает имя линии тренда. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Получает или задает имя линии тренда. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Получает или задает тип линии тренда. Чтение/запись [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Возвращаемое значение:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Получает или задает тип линии тренда. Чтение/запись [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Представляет формат линии тренда. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Возвращаемое значение:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Представляет формат линии тренда. Чтение/запись [IFormat](../../com.aspose.slides/iformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается до данных серии, к которой применяется тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Возвращаемое значение:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается до данных серии, к которой применяется тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается после данных серии, к которой применяется тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Возвращаемое значение:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Указывает количество категорий (или единиц на диаграмме разброса), на которое линия тренда простирается после данных серии, к которой применяется тренд. На диаграммах разброса и неразбросных диаграммах значение должно быть неотрицательным. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Указывает значение, где линия тренда пересекает ось y. Это свойство поддерживается только когда тип линии тренда — exp, linear или poly. Чтение/запись double.

**Возвращаемое значение:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Указывает значение, где линия тренда пересекает ось y. Это свойство поддерживается только когда тип линии тренда — exp, linear или poly. Чтение/запись double.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Указывает, что уравнение линии тренда отображается на диаграмме (в той же метке, что и Rsquaredvalue). Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Указывает, что уравнение линии тренда отображается на диаграмме (в той же метке, что и Rsquaredvalue). Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Указывает порядок полиномиальной линии тренда. Игнорируется для остальных типов линий тренда. Значение должно быть от 2 до 6. Чтение/запись byte.

**Возвращаемое значение:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Указывает порядок полиномиальной линии тренда. Игнорируется для остальных типов линий тренда. Значение должно быть от 2 до 6. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Указывает период линии тренда для линии скользящего среднего. Игнорируется для остальных вариантов линии тренда. Значение должно быть от 2 до 255. Чтение/запись byte.

**Возвращаемое значение:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Указывает период линии тренда для линии скользящего среднего. Игнорируется для остальных вариантов линии тренда. Значение должно быть от 2 до 255. Чтение/запись byte.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Указывает, что значение R-squared линии тренда отображается на диаграмме (в той же метке, что и уравнение). Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Указывает, что значение R-squared линии тренда отображается на диаграмме (в той же метке, что и уравнение). Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Представляет элемент легенды, связанный с этой линией тренда, только для чтения [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Возвращаемое значение:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)