---
title: IChartTitle
second_title: Aspose.Slides для Android через справку API Java
description: Представляет свойства заголовка диаграммы.
type: docs
url: /ru/com.aspose.slides/icharttitle/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

Представляет свойства заголовка диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getOverlay()](#getOverlay--) | Определяет, разрешено ли другим элементам диаграммы перекрывать заголовок. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Определяет, разрешено ли другим элементам диаграммы перекрывать заголовок. |
| [getFormat()](#getFormat--) | Возвращает стили заливки, линии и эффекта заголовка. |

### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Определяет, разрешено ли другим элементам диаграммы перекрывать заголовок. Чтение/запись boolean.

**Возвращает:**
boolean

### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Определяет, разрешено ли другим элементам диаграммы перекрывать заголовок. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Возвращает стили заливки, линии и эффекта заголовка. Только чтение [IFormat](../../com.aspose.slides/iformat).

**Возвращает:**
[IFormat](../../com.aspose.slides/iformat)