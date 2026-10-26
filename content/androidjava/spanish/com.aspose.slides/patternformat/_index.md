---
title: PatternFormat
second_title: Aspose.Slides para Android vía Referencia de API Java
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
| [getForeColor()](#getForeColor--) | Devuelve el color del patrón de primer plano. |
| [getBackColor()](#getBackColor--) | Devuelve el color del patrón de fondo. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Crea una imagen de mosaico para el relleno del patrón con colores especificados. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Crea una imagen de mosaico para el relleno del patrón. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versión. Sólo lectura long.

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


Devuelve el color del patrón de primer plano. Sólo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


Devuelve el color del patrón de fondo. Sólo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```


Crea una imagen de mosaico para el relleno del patrón con colores especificados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| background | java.lang.Integer | El java.lang.Integer de fondo para el patrón. |
| foreground | java.lang.Integer | El java.lang.Integer de primer plano para el patrón. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```


Crea una imagen de mosaico para el relleno del patrón.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| styleColor | java.lang.Integer | El java.lang.Integer predeterminado |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).