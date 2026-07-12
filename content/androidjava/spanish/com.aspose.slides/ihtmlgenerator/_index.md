---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Generador HTML.
type: docs
url: /es/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Generador HTML.
## Métodos

| Método | Descripción |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Agrega texto HTML formateado. |
| [addHtml(char[] html)](#addHtml-char---) | Agrega texto HTML formateado. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Agrega texto HTML formateado. |
| [addText(String text)](#addText-java.lang.String-) | Agrega texto sin formato a los archivos HTML, reemplazando caracteres especiales con entidades HTML. |
| [addText(char[] text)](#addText-char---) | Agrega texto sin formato a los archivos HTML, reemplazando caracteres especiales con entidades HTML. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Agrega texto sin formato a los archivos HTML, reemplazando caracteres especiales con entidades HTML. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Cita el valor del atributo y lo agrega al archivo HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Cita el valor del atributo y lo agrega al archivo HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Cita el valor del atributo y lo agrega al archivo HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | Devuelve el tamaño de la imagen de la diapositiva. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Devuelve una unidad en la que se especifica el tamaño de la imagen de la diapositiva. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Devuelve un código css de la unidad en la que se especifica el tamaño de la imagen de la diapositiva. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Devuelve el índice de la diapositiva previamente renderizada o -1 si se está renderizando la primera diapositiva. |
| [getSlideIndex()](#getSlideIndex--) | Devuelve el índice de la diapositiva que se está renderizando actualmente. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Devuelve el índice de una diapositiva que se renderizará después de la diapositiva actual o -1 si actualmente se está renderizando la última diapositiva. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Agrega texto HTML formateado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| html | java.lang.String | Texto a agregar. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Agrega texto HTML formateado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| html | char[] | Texto a agregar. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
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
public abstract void addText(String text)
```

Agrega texto sin formato a los archivos HTML, reemplazando caracteres especiales con entidades HTML. Los saltos de línea y los espacios en blanco no se reemplazan.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a agregar. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Agrega texto sin formato a los archivos HTML, reemplazando caracteres especiales con entidades HTML. Los saltos de línea y los espacios en blanco no se reemplazan.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | char[] | Texto a agregar. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Agrega texto sin formato a los archivos HTML, reemplazando caracteres especiales con entidades HTML. Los saltos de línea y los espacios en blanco no se reemplazan.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | char[] | Texto a agregar. |
| startIndex | int | Índice inicial de la porción a agregar. |
| length | int | Longitud de la porción a agregar. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Cita el valor del atributo y lo agrega al archivo HTML.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String | Cadena de valor del atributo. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Cita el valor del atributo y lo agrega al archivo HTML.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char[] | Cadena de valor del atributo. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Cita el valor del atributo y lo agrega al archivo HTML.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char[] | Cadena de valor del atributo. |
| startIndex | int | Índice inicial de la porción a agregar. |
| length | int | Longitud de la porción a agregar. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

Devuelve el tamaño de la imagen de la diapositiva. Solo lectura [SizeF](../../com.aspose.slides.android/sizef).

**Devuelve:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Devuelve una unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lectura [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Devuelve:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Devuelve un código css de la unidad en la que se especifica el tamaño de la imagen de la diapositiva. Solo lectura String.

**Devuelve:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Devuelve el índice de la diapositiva previamente renderizada o -1 si se está renderizando la primera diapositiva. Solo lectura int.

**Devuelve:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Devuelve el índice de la diapositiva que se está renderizando actualmente. Solo lectura int.

**Devuelve:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Devuelve el índice de una diapositiva que se renderizará después de la diapositiva actual o -1 si actualmente se está renderizando la última diapositiva. Solo lectura int.

**Devuelve:**
int