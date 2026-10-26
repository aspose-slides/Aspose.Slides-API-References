---
title: IParagraphCollection
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa una colección de párrafos.
type: docs
url: /es/com.aspose.slides/iparagraphcollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Representa una colección de párrafos.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [getCount()](#getCount--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Agrega un Paragraph al final de la colección. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Agrega un contenido de ParagraphCollection al final de la colección. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Inserta un Paragraph en la colección en el índice especificado. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Inserta un contenido de ParagraphCollection en la colección en el índice especificado. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Elimina la primera aparición de un párrafo específico. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Agrega texto de una cadena html especificada a la colección. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Agrega texto de una cadena html especificada a la colección. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Convierte los párrafos especificados a HTML y lo devuelve como objeto String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Obtiene el número de elementos realmente contenidos en la colección. int de solo lectura.

**Devuelve:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Agrega un Paragraph al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | El Paragraph que se agregará al final de la colección. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Agrega un contenido de ParagraphCollection al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | El ParagraphCollection que se agregará al final de la colección. |

**Devuelve:**
int - El índice en el que se ha agregado el Paragraph o -1 si no hay nada que agregar.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Inserta un Paragraph en la colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se debe insertar el Paragraph. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | El Paragraph a insertar. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Inserta un contenido de ParagraphCollection en la colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se deben insertar los párrafos. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Los párrafos a insertar. |

### clear() {#clear--}
```
public abstract void clear()
```

Elimina todos los elementos de la colección.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina el elemento en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Elimina la primera aparición de un párrafo específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | El párrafo a eliminar de la colección. |

**Devuelve:**
boolean - true si el elemento se eliminó correctamente; de lo contrario, false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Agrega texto de una cadena html especificada a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Agrega texto de una cadena html especificada a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de devolución de llamada del resolvedor que resuelve URIs y recupera los objetos referenciados. |
| uri | java.lang.String | URI para agregar el documento HTML. Utilizado para resolver enlaces relativos.

---

Especificar el resolvedor puede introducir potencialmente una vulnerabilidad. Úselo con precaución. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Convierte los párrafos especificados a HTML y lo devuelve como objeto String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstParagraphIndex | int | Índice del primer párrafo int |
| paragraphsCount | int | Número de párrafos int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Opciones de conversión [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Devuelve:**
java.lang.String - HTML generado.