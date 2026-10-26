---
title: PatternFormat
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет шаблон для заполнения фигуры.
type: docs
url: /ru/com.aspose.slides/patternformat/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Представляет шаблон для заполнения фигуры.
## Методы

| Метод | Описание |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Возвращает или задает стиль шаблона. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Возвращает или задает стиль шаблона. |
| [getForeColor()](#getForeColor--) | Возвращает цвет переднего плана шаблона. |
| [getBackColor()](#getBackColor--) | Возвращает цвет фона шаблона. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Создаёт изображение тайла для заполнения шаблоном с указанными цветами. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Создаёт изображение тайла для заполнения шаблоном. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Версия. Только для чтения long.

**Возвращаемое значение:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```


Возвращает или задает стиль шаблона. Чтение/запись [PatternStyle](../../com.aspose.slides/patternstyle).

**Возвращаемое значение:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```


Возвращает или задает стиль шаблона. Чтение/запись [PatternStyle](../../com.aspose.slides/patternstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```


Возвращает цвет переднего плана шаблона. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


Возвращает цвет фона шаблона. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```


Создаёт изображение тайла для заполнения шаблоном с указанными цветами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| background | java.lang.Integer | Значение java.lang.Integer, задающее фон шаблона. |
| foreground | java.lang.Integer | Значение java.lang.Integer, задающее передний план шаблона. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - Тайл [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```


Создаёт изображение тайла для заполнения шаблоном.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.lang.Integer | Значение java.lang.Integer, задающее значение по умолчанию. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - Тайл [IImage](../../com.aspose.slides/iimage).