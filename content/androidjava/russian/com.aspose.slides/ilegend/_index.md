---
title: ILegend
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет свойства легенды диаграмм.
type: docs
url: /ru/com.aspose.slides/ilegend/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Представляет свойства легенды диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getOverlay()](#getOverlay--) | Определяет, разрешено ли другим элементам диаграммы перекрывать легенду. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Определяет, разрешено ли другим элементам диаграммы перекрывать легенду. |
| [getPosition()](#getPosition--) | Указывает позицию легенды на диаграмме. |
| [setPosition(int value)](#setPosition-int-) | Указывает позицию легенды на диаграмме. |
| [getFormat()](#getFormat--) | Возвращает формат легенды. |
| [getEntries()](#getEntries--) | Получает элементы легенды. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Определяет, разрешено ли другим элементам диаграммы перекрывать легенду. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Определяет, разрешено ли другим элементам диаграммы перекрывать легенду. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Указывает позицию легенды на диаграмме. Значения X, Y, Width, Heigt, отличные от NaN, переопределяют эффект этого свойства. Чтение/запись [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Возвращаемое значение:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Указывает позицию легенды на диаграмме. Значения X, Y, Width, Heigt, отличные от NaN, переопределяют эффект этого свойства. Чтение/запись [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Возвращает формат легенды. Только чтение [IFormat](../../com.aspose.slides/iformat).

**Возвращаемое значение:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Получает элементы легенды. Только чтение [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Возвращаемое значение:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)