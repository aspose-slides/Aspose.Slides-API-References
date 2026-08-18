---
title: PatternFormat
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un patrón para rellenar una forma.
type: docs
url: /es/com.aspose.slides/patternformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Representa un patrón para rellenar una forma.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Devuelve o establece el estilo del patrón. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Devuelve o establece el estilo del patrón. |
| [getForeColor()](#getForeColor--) | Devuelve el color de patrón de primer plano. |
| [getBackColor()](#getBackColor--) | Devuelve el color de patrón de fondo. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Crea una imagen de mosaico para el relleno del patrón con colores especificados. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Crea una imagen de mosaico para el relleno del patrón. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Long de solo lectura.

**Devuelve:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Devuelve o establece el estilo del patrón. Lectura/escritura [PatternStyle](../../com.aspose.slides/patternstyle).

**Devuelve:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Devuelve o establece el estilo del patrón. Lectura/escritura [PatternStyle](../../com.aspose.slides/patternstyle).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Devuelve el color de patrón de primer plano. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Devuelve el color de patrón de fondo. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```

Crea una imagen de mosaico para el relleno del patrón con colores especificados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| background | java.awt.Color | El java.awt.Color de fondo para el patrón. |
| foreground | java.awt.Color | El java.awt.Color de primer plano para el patrón. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```

Crea una imagen de mosaico para el relleno del patrón.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| styleColor | java.awt.Color | El java.awt.Color predeterminado |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).