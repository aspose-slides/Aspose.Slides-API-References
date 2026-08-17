---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Представляет узор для заполнения фигуры.
type: docs
url: /ru/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Представляет узор для заполнения фигуры.
## Методы

| Method | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Возвращает или задаёт стиль узора. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Возвращает или задаёт стиль узора. |
| [getForeColor()](#getForeColor--) | Возвращает цвет переднего плана узора. |
| [getBackColor()](#getBackColor--) | Возвращает цвет фона узора. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Создаёт изображение-тайл для заливки узором с указанными цветами. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Создаёт изображение-тайл для заливки узором. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Возвращает или задаёт стиль узора. Чтение/запись [PatternStyle](../../com.aspose.slides/patternstyle).

**Возврат:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Возвращает или задаёт стиль узора. Чтение/запись [PatternStyle](../../com.aspose.slides/patternstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Возвращает цвет переднего плана узора. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возврат:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Возвращает цвет фона узора. Только для чтения [IColorFormat](../../com.aspose.slides/icolorformat).

**Возврат:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

Создаёт изображение-тайл для заливки узором с указанными цветами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| background | java.awt.Color | Фоновый java.awt.Color для узора. |
| foreground | java.awt.Color | Передний java.awt.Color для узора. |

**Возврат:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

Создаёт изображение-тайл для заливки узором.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| styleColor | java.awt.Color | Цвет java.awt.Color по умолчанию, определённый в объекте StyleEx ShapeEx. Цвета заливки могут зависеть от него. |

**Возврат:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.