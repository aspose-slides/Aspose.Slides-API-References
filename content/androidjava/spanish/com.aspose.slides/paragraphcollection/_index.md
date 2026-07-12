---
title: ParagraphCollection
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa una colección de párrafos.
type: docs
url: /es/com.aspose.slides/paragraphcollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
```
public final class ParagraphCollection extends DomObject<TextFrame> implements IParagraphCollection
```

Representa una colección de párrafos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [isReadOnly()](#isReadOnly--) | Obtiene un valor que indica si el [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Añade un Paragraph al final de la colección. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Añade el contenido de ParagraphCollection al final de la colección. |
| [indexOf(IParagraph item)](#indexOf-com.aspose.slides.IParagraph-) | Determina el índice de un elemento específico en la List. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Inserta un Paragraph en la colección en el índice especificado. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Inserta el contenido de ParagraphCollection en la colección en el índice especificado. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [contains(IParagraph item)](#contains-com.aspose.slides.IParagraph-) | Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico. |
| [copyTo(IParagraph[] array, int arrayIndex)](#copyTo-com.aspose.slides.IParagraph---int-) | Copia los elementos de [IGenericCollection](../../com.aspose.slides/igenericcollection) a un Array, empezando en un índice de Array específico. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Elimina la primera aparición de un objeto específico del [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [getSlide()](#getSlide--) | Devuelve la diapositiva principal de una colección de párrafos. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación principal de una colección de párrafos. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Añade texto desde la cadena html especificada a la colección. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Añade texto desde la cadena html especificada a la colección. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Convierte los párrafos especificados a HTML y lo devuelve como objeto String. |
### getCount() {#getCount--}
```
public final int getCount()
```

Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int.

**Devuelve:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtiene un valor que indica si el [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. Solo lectura boolean.

**Devuelve:**
boolean - true si el [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura; de lo contrario, false.
### get_Item(int index) {#get-Item-int-}
```
public final IParagraph get_Item(int index)
```

Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IParagraph](../../com.aspose.slides/iparagraph)
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public final void add(IParagraph value)
```

Añade un Paragraph al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | El Paragraph que se añadirá al final de la colección. |

### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public final int add(IParagraphCollection value)
```

Añade el contenido de ParagraphCollection al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | El ParagraphCollection que se añadirá al final de la colección. |

**Devuelve:**
int - El índice en el que se ha añadido el Paragraph o -1 si no hay nada que añadir.
### indexOf(IParagraph item) {#indexOf-com.aspose.slides.IParagraph-}
```
public final int indexOf(IParagraph item)
```

Determina el índice de un elemento específico en la List.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | El objeto a localizar en la List. |

**Devuelve:**
int - El índice del elemento si se encuentra en la lista; de lo contrario, -1.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public final void insert(int index, IParagraph value)
```

Inserta un Paragraph en la colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se debe insertar el Paragraph. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | El Paragraph a insertar. |

### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public final void insert(int index, IParagraphCollection value)
```

Inserta el contenido de ParagraphCollection en la colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero en el que se deben insertar los párrafos. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Los párrafos a insertar. |

### clear() {#clear--}
```
public final void clear()
```

Elimina todos los elementos de la colección.

### contains(IParagraph item) {#contains-com.aspose.slides.IParagraph-}
```
public final boolean contains(IParagraph item)
```

Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | El objeto a localizar en el [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true si el elemento se encuentra en el [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, false.
### copyTo(IParagraph[] array, int arrayIndex) {#copyTo-com.aspose.slides.IParagraph---int-}
```
public final void copyTo(IParagraph[] array, int arrayIndex)
```

Copia los elementos de [IGenericCollection](../../com.aspose.slides/igenericcollection) a un Array, comenzando en un índice de Array específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [IParagraph\[\]](../../com.aspose.slides/iparagraph) | El Array unidimensional que es el destino de los elementos copiados desde [IGenericCollection](../../com.aspose.slides/igenericcollection). El Array debe tener indexado basado en cero. |
| arrayIndex | int | El índice basado en cero en el array en el que comienza la copia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina el elemento en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public final boolean remove(IParagraph item)
```

Elimina la primera aparición de un objeto específico del [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | El objeto a eliminar del [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true si el elemento se eliminó correctamente del [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, false. Este método también devuelve false si el elemento no se encuentra en el [IGenericCollection](../../com.aspose.slides/igenericcollection) original.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IParagraph> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IParagraph> - Un java.util.Iterator para toda la colección.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva principal de una colección de párrafos. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación principal de una colección de párrafos. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public final void addFromHtml(String text)
```

Añade texto desde la cadena html especificada a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto HTML. |

### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Añade texto desde la cadena html especificada a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto HTML. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objeto de callback resolver que resuelve URIs y recupera objetos referenciados. |
| uri | java.lang.String | URI para añadir el documento HTML. Usado para resolver enlaces relativos.

--------------------
Especificar el resolvedor puede introducir potencialmente una vulnerabilidad. Úselo con precaución. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public final String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Convierte los párrafos especificados a HTML y lo devuelve como objeto String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstParagraphIndex | int | Índice del primer párrafo int |
| paragraphsCount | int | Recuento de párrafos int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Opciones de conversión [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Devuelve:**
java.lang.String - HTML generado.