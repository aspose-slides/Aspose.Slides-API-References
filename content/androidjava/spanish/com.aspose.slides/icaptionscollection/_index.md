---
title: ICaptionsCollection
second_title: Referencia de API de Java para Aspose.Slides para Android
description: Representa una colección de los subtítulos cerrados.
type: docs
url: /es/com.aspose.slides/icaptionscollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
```

Representa una colección de los subtítulos cerrados.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve los subtítulos cerrados en el índice especificado. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Añade subtítulos cerrados WebVTT al final de la colección. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Añade subtítulos cerrados WebVTT al final de la colección desde una secuencia. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Elimina los subtítulos cerrados especificados de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina los subtítulos cerrados en el índice especificado. |
| [clear()](#clear--) | Elimina todos los subtítulos cerrados de la colección. |
| [getCount()](#getCount--) | Devuelve el número de elementos en la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
```

Devuelve los subtítulos cerrados en el índice especificado. Sólo lectura [ICaptions](../../com.aspose.slides/icaptions).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public abstract ICaptions add(String label, String filePath)
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
public abstract ICaptions add(String label, InputStream stream)
```

Añade subtítulos cerrados WebVTT al final de la colección desde una secuencia.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| label | java.lang.String | La etiqueta de los subtítulos cerrados. |
| stream | java.io.InputStream | La secuencia de entrada que contiene datos en formato WebVTT. |

**Devuelve:**
[ICaptions](../../com.aspose.slides/icaptions) - La instancia [ICaptions](../../com.aspose.slides/icaptions) añadida.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

Elimina los subtítulos cerrados especificados de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Los subtítulos cerrados a eliminar. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina los subtítulos cerrados en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice de los subtítulos cerrados a eliminar. |

### clear() {#clear--}
```
public abstract void clear()
```

Elimina todos los subtítulos cerrados de la colección.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Devuelve el número de elementos en la colección. Sólo lectura int .

**Devuelve:**
int