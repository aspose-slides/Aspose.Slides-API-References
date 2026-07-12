---
title: TagCollection
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa la colección de etiquetas (pares de cadenas definidos por el usuario)
type: docs
url: /es/com.aspose.slides/tagcollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Representa la colección de etiquetas (pares de cadenas definidos por el usuario)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve un número de etiquetas en la colección. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Añade una nueva etiqueta a la colección. |
| [remove(String name)](#remove-java.lang.String-) | Elimina la etiqueta con un nombre especificado de la colección. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Devuelve el índice basado en cero de la clave especificada en la colección. |
| [contains(String name)](#contains-java.lang.String-) | Determina si la colección contiene un nombre específico. |
| [removeAt(int index)](#removeAt-int-) | Elimina la etiqueta en el índice especificado. |
| [clear()](#clear--) | Elimina todas las etiquetas de la colección. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Devuelve el valor de una etiqueta en el índice especificado. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Devuelve la clave de una etiqueta en el índice especificado. |
| [getNamesOfTags()](#getNamesOfTags--) | Devuelve los nombres de las etiquetas. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Devuelve o establece un par clave-valor de una etiqueta. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Devuelve o establece un par clave-valor de una etiqueta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### size() {#size--}
```
public final int size()
```

Devuelve un número de etiquetas en la colección. Solo lectura int.

**Devuelve:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

Añade una nueva etiqueta a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre de la etiqueta. |
| value | java.lang.String | El valor de la etiqueta. |

**Devuelve:**
int - El índice de la etiqueta añadida.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Elimina la etiqueta con un nombre especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre de la etiqueta a eliminar. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

Devuelve el índice basado en cero de la clave especificada en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre a localizar en la colección. |

**Devuelve:**
int - El índice basado en cero de la clave, si se encuentra en la colección; de lo contrario, -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

Determina si la colección contiene un nombre específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | La clave a localizar. |

**Devuelve:**
boolean - Verdadero si la colección contiene una etiqueta con la clave especificada; de lo contrario, falso.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina la etiqueta en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero de la etiqueta a eliminar. |
### clear() {#clear--}
```
public final void clear()
```

Elimina todas las etiquetas de la colección.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

Devuelve el valor de una etiqueta en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la etiqueta a devolver. |

**Devuelve:**
java.lang.String - Valor de una etiqueta.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

Devuelve la clave de una etiqueta en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la etiqueta a devolver. |

**Devuelve:**
java.lang.String - Clave de una etiqueta.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

Devuelve los nombres de las etiquetas.

**Devuelve:**
java.lang.String[] - Nombres de las etiquetas.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Devuelve o establece un par clave-valor de una etiqueta.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Clave de una etiqueta. |

**Devuelve:**
java.lang.String - Valor de una etiqueta.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Devuelve o establece un par clave-valor de una etiqueta.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Clave de una etiqueta. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array a rellenar. |
| index | int | Posición inicial en el array de destino. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura boolean.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.