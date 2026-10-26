---
title: PatternFormat
second_title: Aspose.Slides для справки API Java
description: Представляет узор для заполнения формы.
type: docs
url: /ru/com.aspose.slides/patternformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Представляет узор для заполнения формы.
## Методы

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Возвращает или задает стиль узора. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Возвращает или задает стиль узора. |
| [getForeColor()](#getForeColor--) | Возвращает цвет переднего плана узора. |
| [getBackColor()](#getBackColor--) | Возвращает цвет фона узора. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Создаёт изображение тайла для заполнения узором с заданными цветами. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Создаёт изображение тайла для заполнения узором. |
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

Возвращает или задает стиль узора. Чтение/запись [PatternStyle](../../com.aspose.slides/patternstyle).

**Возвращаемое значение:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Возвращает или задает стиль узора. Чтение/запись [PatternStyle](../../com.aspose.slides/patternstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Возвращает цвет переднего плана узора. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Возвращает цвет фона узора. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Создаёт изображение тайла для заполнения узором с заданными цветами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| background | java.awt.Color | Фоновый java.awt.Color для узора. |
| foreground | java.awt.Color | Передний java.awt.Color для узора. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Создаёт изображение тайла для заполнения узором.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.awt.Color | Стандартный java.awt.Color |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).