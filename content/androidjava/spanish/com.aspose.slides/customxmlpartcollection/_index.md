---
title: CustomXmlPartCollection
second_title: Referencia de API de Java para Aspose.Slides para Android
description: Representa una colección de partes XML personalizadas.
type: docs
url: /es/com.aspose.slides/customxmlpartcollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Representa una colección de partes XML personalizadas.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the element at the specified index. |
| [size()](#size--) | Returns count of custom xml parts in the collection. |
| [add(String xmlString)](#add-java.lang.String-) | Adds new custom xml part. |
| [add(byte[] xmlData)](#add-byte---) | Adds new custom xml part. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Adds new custom xml part. |
| [removeAt(int index)](#removeAt-int-) | Removes custom xml part at the specified index. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Removes the first occurrence of a specific object from the collection. |
| [clear()](#clear--) | Removes all items from the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copy to specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```


Devuelve el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a obtener. |

**Devuelve:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - El elemento en el índice especificado.
### size() {#size--}
```
public final int size()
```


Devuelve el recuento de partes XML personalizadas en la colección. int de solo lectura.

**Devuelve:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```


Agrega una nueva parte XML personalizada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlString | java.lang.String | La cadena XML de la nueva parte que se agregará. |

**Devuelve:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte XML personalizada creada.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```


Agrega una nueva parte XML personalizada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlData | byte[] | Los datos XML de la nueva parte que se agregarán. |

**Devuelve:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte XML personalizada creada.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```


Agrega una nueva parte XML personalizada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | java.io.InputStream | El InputStream con los datos XML de la nueva parte que se agregará. |

**Devuelve:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte XML personalizada creada.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina la parte XML personalizada en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```


Elimina la primera aparición de un objeto específico de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | La parte XML personalizada a eliminar. |

**Devuelve:**
boolean - true si el elemento se elimina correctamente; de lo contrario, false.
### clear() {#clear--}
```
public final void clear()
```


Elimina todos los elementos de la colección.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia a la matriz especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Matriz a la que copiar. |
| index | int | Índice para comenzar la copia. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para hilos). boolean de solo lectura.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Devuelve una raíz de sincronización. Object de solo lectura.

**Devuelve:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Un IGenericEnumerator que puede usarse para recorrer la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Una java.util.Iterator para toda la colección.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. IDOMObject de solo lectura.

**Devuelve:**
com.aspose.slides.IDOMObject