---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет шаблон для заполнения фигуры.
type: docs
url: /ru/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Представляет шаблон для заполнения фигуры.
## Методы

| Метод | Описание |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Возвращает или задаёт стиль шаблона. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Возвращает или задаёт стиль шаблона. |
| [getForeColor()](#getForeColor--) | Возвращает цвет переднего шаблона. |
| [getBackColor()](#getBackColor--) | Возвращает цвет фонового шаблона. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Создаёт изображение плитки для заливки шаблоном с указанными цветами. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Создаёт изображение плитки для заливки шаблоном. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Возвращает или задаёт стиль шаблона. Чтение/запись [PatternStyle](../../com.aspose.slides/patternstyle).

**Возвращаемое значение:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Возвращает или задаёт стиль шаблона. Чтение/запись [PatternStyle](../../com.aspose.slides/patternstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Возвращает цвет переднего шаблона. Только чтение [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Возвращает цвет фонового шаблона. Только чтение [IColorFormat](../../com.aspose.slides/icolorformat).

**Возвращаемое значение:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

Создаёт изображение плитки для заливки шаблоном с указанными цветами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| background | java.lang.Integer | Фоновый java.lang.Integer для шаблона. |
| foreground | java.lang.Integer | Передний java.lang.Integer для шаблона. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - Плитка android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

Создаёт изображение плитки для заливки шаблоном.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.lang.Integer | Стандартный java.lang.Integer, определённый в объекте StyleEx класса ShapeEx. Цвета заливки могут зависеть от него. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - Плитка android.graphics.Bitmap.