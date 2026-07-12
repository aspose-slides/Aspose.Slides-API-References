---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android vía Referencia de API Java
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
| [getForeColor()](#getForeColor--) | Devuelve el color de patrón en primer plano. |
| [getBackColor()](#getBackColor--) | Devuelve el color de patrón en segundo plano. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Crea una imagen de mosaico para el relleno de patrón con colores especificados. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Devuelve el estilo del patrón. Solo lectura [PatternStyle](../../com.aspose.slides/patternstyle).

**Devuelve:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```

Devuelve el color de patrón en primer plano. Solo lectura java.lang.Integer.

**Devuelve:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```

Devuelve el color de patrón en segundo plano. Solo lectura java.lang.Integer.

**Devuelve:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```

Crea una imagen de mosaico para el relleno de patrón con colores especificados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| background | java.lang.Integer | El java.lang.Integer de fondo para el patrón. |
| foreground | java.lang.Integer | El java.lang.Integer de primer plano para el patrón. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Mosaico [IImage](../../com.aspose.slides/iimage).