---
title: IPatternFormatEffectiveData
second_title: Referencia de API de Aspose.Slides para Java
description: Objeto inmutable que contiene propiedades efectivas de relleno de patrón.
type: docs
url: /es/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Objeto inmutable que contiene propiedades efectivas de relleno de patrón.

--------------------

Esta interfaz se usa como parte de [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) y [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Métodos

| Método | Descripción |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Devuelve el estilo del patrón. |
| [getForeColor()](#getForeColor--) | Devuelve el color del patrón de primer plano. |
| [getBackColor()](#getBackColor--) | Devuelve el color del patrón de fondo. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Crea una imagen de mosaico para el relleno de patrón con colores especificados. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Devuelve el estilo del patrón. Solo lectura [PatternStyle](../../com.aspose.slides/patternstyle).

**Devuelve:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


Devuelve el color del patrón de primer plano. Solo lectura java.awt.Color.

**Devuelve:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


Devuelve el color del patrón de fondo. Solo lectura java.awt.Color.

**Devuelve:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


Crea una imagen de mosaico para el relleno de patrón con colores especificados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| background | java.awt.Color | El java.awt.Color de fondo para el patrón. |
| foreground | java.awt.Color | El java.awt.Color de primer plano para el patrón. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).