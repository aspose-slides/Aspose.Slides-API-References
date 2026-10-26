---
title: CaptionsCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una colección de los subtítulos cerrados.
type: docs
url: /es/com.aspose.slides/captionscollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Representa una colección de los subtítulos cerrados.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve los subtítulos cerrados en el índice especificado. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Añade subtítulos cerrados WebVTT al final de la colección. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Añade subtítulos cerrados WebVTT al final de la colección desde un flujo. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Elimina los subtítulos cerrados especificados de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina los subtítulos cerrados en el índice especificado. |
| [clear()](#clear--) | Elimina todos los subtítulos cerrados de la colección. |
| [getCount()](#getCount--) | Devuelve el número de elementos en la colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```


Devuelve los subtítulos cerrados en el índice especificado. Solo lectura [ICaptions](../../com.aspose.slides/icaptions).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```


Añade subtítulos cerrados WebVTT al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | java.lang.String | La etiqueta de los subtítulos cerrados. |
| filePath | java.lang.String | La ruta al archivo WebVTT. |

**Devuelve:**
[ICaptions](../../com.aspose.slides/icaptions) - La instancia [ICaptions](../../com.aspose.slides/icaptions) añadida.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```


Añade subtítulos cerrados WebVTT al final de la colección desde un flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | java.lang.String | La etiqueta de los subtítulos cerrados. |
| stream | java.io.InputStream | El flujo de entrada que contiene datos en formato WebVTT. |

**Devuelve:**
[ICaptions](../../com.aspose.slides/icaptions) - La instancia [ICaptions](../../com.aspose.slides/icaptions) añadida.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```


Elimina los subtítulos cerrados especificados de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Los subtítulos cerrados a eliminar. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina los subtítulos cerrados en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice de los subtítulos cerrados a eliminar. |

### clear() {#clear--}
```
public final void clear()
```


Elimina todos los subtítulos cerrados de la colección.

### getCount() {#getCount--}
```
public final int getCount()
```


Devuelve el número de elementos en la colección. Solo lectura int .

**Devuelve:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - A  System.Collections.Generic.IEnumerator1  that can be used to iterate through the collection.