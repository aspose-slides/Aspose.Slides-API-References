---
title: ITagCollection
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa la colección de etiquetas, pares de cadenas definidos por el usuario
type: docs
url: /es/com.aspose.slides/itagcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Representa la colección de etiquetas (pares de cadenas definidas por el usuario)
## Métodos

| Método | Descripción |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Agrega una nueva etiqueta a la colección. |
| [remove(String name)](#remove-java.lang.String-) | Elimina la etiqueta con un nombre especificado de la colección. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Devuelve el índice basado en cero de la clave especificada en la colección. |
| [contains(String name)](#contains-java.lang.String-) | Determina si la colección contiene un nombre específico. |
| [removeAt(int index)](#removeAt-int-) | Elimina la etiqueta en el índice especificado. |
| [clear()](#clear--) | Elimina todas las etiquetas de la colección. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Devuelve el valor de una etiqueta en el índice especificado. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Devuelve la clave de una etiqueta en el índice especificado. |
| [getNamesOfTags()](#getNamesOfTags--) | Devuelve nombres de etiquetas. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Devuelve o establece un par clave-valor de una etiqueta. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Devuelve o establece un par clave-valor de una etiqueta. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Agrega una nueva etiqueta a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre de la etiqueta. |
| value | java.lang.String | El valor de la etiqueta. |

**Devuelve:**
int - El índice de la etiqueta agregada.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Elimina la etiqueta con un nombre especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre de la etiqueta a eliminar. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

Devuelve el índice basado en cero de la clave especificada en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre a buscar en la colección. |

**Devuelve:**
int - El índice basado en cero de la clave, si la clave se encuentra en la colección; de lo contrario, -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Determina si la colección contiene un nombre específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | La clave a buscar. |

**Devuelve:**
boolean - True si la colección contiene una etiqueta con la clave especificada; de lo contrario, false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina la etiqueta en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero de la etiqueta a eliminar. |
### clear() {#clear--}
```
public abstract void clear()
```

Elimina todas las etiquetas de la colección.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
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
public abstract String getNameByIndex(int index)
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
public abstract String[] getNamesOfTags()
```

Devuelve nombres de etiquetas.

**Devuelve:**
java.lang.String[] - Nombres de etiquetas.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```

Devuelve o establece un par clave-valor de una etiqueta.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Clave de una etiqueta. |
| value | java.lang.String |  |