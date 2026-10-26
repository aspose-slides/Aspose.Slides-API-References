---
title: HtmlGenerator
second_title: Referencia de API de Aspose.Slides para Java
description: Generador HTML.
type: docs
url: /es/com.aspose.slides/htmlgenerator/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Generador HTML.
## Métodos

| Método | Descripción |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Añade texto HTML formateado. |
| [addHtml(char[] html)](#addHtml-char---) | Añade texto HTML formateado. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Añade texto HTML formateado. |
| [addText(String text)](#addText-java.lang.String-) | Añade texto plano a los archivos HTML, sustituyendo los caracteres especiales por entidades HTML. |
| [addText(char[] text)](#addText-char---) | Añade texto plano a los archivos HTML, sustituyendo los caracteres especiales por entidades HTML. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Añade texto plano a los archivos HTML, sustituyendo los caracteres especiales por entidades HTML. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Cita el valor del atributo y lo añade al archivo HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Cita el valor del atributo y lo añade al archivo HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Cita el valor del atributo y lo añade al archivo HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | Devuelve el tamaño de la imagen de la diapositiva. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Devuelve la unidad en la que se especifica el tamaño de la imagen de la diapositiva. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Devuelve el código CSS de la unidad en la que se especifica el tamaño de la imagen de la diapositiva. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Devuelve el índice de la diapositiva renderizada previamente o -1 si se está renderizando la primera diapositiva. |
| [getSlideIndex()](#getSlideIndex--) | Devuelve el índice de la diapositiva que se está renderizando actualmente. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Devuelve el índice de una diapositiva que se renderizará después de la diapositiva actual o -1 si la diapositiva actual es la última. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Añade texto HTML formateado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| html | java.lang.String | Texto a añadir. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Añade texto HTML formateado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| html | char[] | Texto a añadir. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Añade texto HTML formateado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| html | char[] | Texto a añadir. |
| startIndex | int | Índice inicial de la porción a añadir. |
| length | int | Longitud de la porción a añadir. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Añade texto plano a los archivos HTML, sustituyendo los caracteres especiales por entidades HTML. Los saltos de línea y los espacios en blanco no se sustituyen.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a añadir. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Añade texto plano a los archivos HTML, sustituyendo los caracteres especiales por entidades HTML. Los saltos de línea y los espacios en blanco no se sustituyen.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | char[] | Texto a añadir. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Añade texto plano a los archivos HTML, sustituyendo los caracteres especiales por entidades HTML. Los saltos de línea y los espacios en blanco no se sustituyen.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | char[] | Texto a añadir. |
| startIndex | int | Índice inicial de la porción a añadir. |
| length | int | Longitud de la porción a añadir. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Cita el valor del atributo y lo añade al archivo HTML.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String | Cadena con el valor del atributo. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Cita el valor del atributo y lo añade al archivo HTML.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char[] | Cadena con el valor del atributo. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Cita el valor del atributo y lo añade al archivo HTML.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char[] | Cadena con el valor del atributo. |
| startIndex | int | Índice inicial de la porción a añadir. |
| length | int | Longitud de la porción a añadir. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```

Devuelve el tamaño de la imagen de la diapositiva. Solo lectura java.awt.geom.Dimension2D.

**Devuelve:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Devuelve una unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lectura [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Devuelve:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Devuelve el código CSS de la unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lectura String.

**Devuelve:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Devuelve el índice de la diapositiva renderizada previamente o -1 si se está renderizando la primera diapositiva. Solo lectura int.

**Devuelve:**
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Devuelve el índice de la diapositiva que se está renderizando actualmente. Solo lectura int.

**Devuelve:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Devuelve el índice de una diapositiva que se renderizará después de la diapositiva actual o -1 si la diapositiva actual es la última. Solo lectura int.

**Devuelve:**
int