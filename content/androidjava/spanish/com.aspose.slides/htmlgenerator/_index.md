---
title: HtmlGenerator
second_title: Aspose.Slides para Android a través de la Referencia de la API Java
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
| [addHtml(String html)](#addHtml-java.lang.String-) | Agrega texto HTML formateado. |
| [addHtml(char[] html)](#addHtml-char---) | Agrega texto HTML formateado. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Agrega texto HTML formateado. |
| [addText(String text)](#addText-java.lang.String-) | Agrega texto plano a los archivos html, reemplazando caracteres especiales con entidades html. |
| [addText(char[] text)](#addText-char---) | Agrega texto plano a los archivos html, reemplazando caracteres especiales con entidades html. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Agrega texto plano a los archivos html, reemplazando caracteres especiales con entidades html. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Encierra entre comillas el valor del atributo y lo agrega al archivo html. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Encierra entre comillas el valor del atributo y lo agrega al archivo html. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Encierra entre comillas el valor del atributo y lo agrega al archivo html. |
| [getSlideImageSize()](#getSlideImageSize--) | Devuelve el tamaño de la imagen de la diapositiva. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Devuelve la unidad en la que se especifica el tamaño de la imagen de la diapositiva. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Devuelve un código CSS de la unidad en la que se especifica el tamaño de la imagen de la diapositiva. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Devuelve el índice de la diapositiva previamente renderizada o -1 si se está renderizando la primera diapositiva. |
| [getSlideIndex()](#getSlideIndex--) | Devuelve el índice de la diapositiva que se está renderizando actualmente. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Devuelve el índice de una diapositiva que se renderizará después de la diapositiva actual o -1 si la diapositiva actual es la última. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Agrega texto HTML formateado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| html | java.lang.String | Texto a agregar. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Agrega texto HTML formateado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| html | char[] | Texto a agregar. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Agrega texto HTML formateado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| html | char[] | Texto a agregar. |
| startIndex | int | Índice inicial de la porción a agregar. |
| length | int | Longitud de la porción a agregar. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Agrega texto plano a los archivos html, reemplazando caracteres especiales con entidades html. Los saltos de línea y los espacios en blanco no se reemplazan.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a agregar. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Agrega texto plano a los archivos html, reemplazando caracteres especiales con entidades html. Los saltos de línea y los espacios en blanco no se reemplazan.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | char[] | Texto a agregar. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Agrega texto plano a los archivos html, reemplazando caracteres especiales con entidades html. Los saltos de línea y los espacios en blanco no se reemplazan.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | char[] | Texto a agregar. |
| startIndex | int | Índice inicial de la porción a agregar. |
| length | int | Longitud de la porción a agregar. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Encierra entre comillas el valor del atributo y lo agrega al archivo html.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String | Cadena del valor del atributo. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Encierra entre comillas el valor del atributo y lo agrega al archivo html.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char[] | Cadena del valor del atributo. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Encierra entre comillas el valor del atributo y lo agrega al archivo html.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char[] | Cadena del valor del atributo. |
| startIndex | int | Índice inicial de la porción a agregar. |
| length | int | Longitud de la porción a agregar. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

Devuelve el tamaño de la imagen de la diapositiva. Solo lectura [SizeF](../../com.aspose.slides.android/sizef).

**Devuelve:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Devuelve la unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lectura [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Devuelve:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Devuelve un código CSS de la unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lectura String.

**Devuelve:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Devuelve el índice de la diapositiva previamente renderizada o -1 si se está renderizando la primera diapositiva. Solo lectura int.

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