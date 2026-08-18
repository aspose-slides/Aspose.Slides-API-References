---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
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
| [getPatternStyle()](#getPatternStyle--) | Devuelve o establece el estilo del patrón. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Devuelve o establece el estilo del patrón. |
| [getForeColor()](#getForeColor--) | Devuelve el color de patrón de primer plano. |
| [getBackColor()](#getBackColor--) | Devuelve el color de patrón de fondo. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Crea una imagen de mosaico para el relleno de patrón con colores especificados. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Crea una imagen de mosaico para el relleno de patrón. |
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
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

Crea una imagen de mosaico para el relleno de patrón con colores especificados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| background | java.awt.Color | El color de fondo java.awt.Color para el patrón. |
| foreground | java.awt.Color | El color de primer plano java.awt.Color para el patrón. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Mosaico java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

Crea una imagen de mosaico para el relleno de patrón.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| styleColor | java.awt.Color | El color java.awt.Color predeterminado, definido en el objeto StyleEx de ShapeEx. Los colores de relleno pueden depender de este. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Mosaico java.awt.image.BufferedImage.