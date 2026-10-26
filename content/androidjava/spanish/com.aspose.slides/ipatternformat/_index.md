---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /es/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Representa un patrón para rellenar una forma.
## Métodos

| Método | Descripción |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Returns or sets the pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returns or sets the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Creates a tile image for the pattern fill. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Devuelve o establece el estilo del patrón. Lectura/escritura [PatternStyle](../../com.aspose.slides/patternstyle).

**Devuelve:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Devuelve o establece el estilo del patrón. Lectura/escritura [PatternStyle](../../com.aspose.slides/patternstyle).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Devuelve el color de patrón de primer plano. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Devuelve el color de patrón de fondo. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

Crea una imagen de mosaico para el relleno de patrón con colores especificados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| background | java.lang.Integer | El java.lang.Integer de fondo para el patrón. |
| foreground | java.lang.Integer | El java.lang.Integer de primer plano para el patrón. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Mosaico android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

Crea una imagen de mosaico para el relleno de patrón.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| styleColor | java.lang.Integer | El java.lang.Integer predeterminado, definido en el objeto StyleEx de ShapeEx. Los colores del relleno pueden depender de esto. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Mosaico android.graphics.Bitmap.