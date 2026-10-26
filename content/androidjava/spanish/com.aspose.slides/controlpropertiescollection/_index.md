---
title: ControlPropertiesCollection
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Una colección de propiedades AcitveX.
type: docs
url: /es/com.aspose.slides/controlpropertiescollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Una colección de propiedades AcitveX.
## Métodos

| Método | Descripción |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Agrega una propiedad a la colección. |
| [remove(String name)](#remove-java.lang.String-) | Elimina una propiedad con el nombre especificado. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Devuelve o establece la propiedad. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Devuelve o establece la propiedad. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Devuelve la colección de nombres de propiedades. |
| [clear()](#clear--) | Elimina todas las propiedades. |
| [getCount()](#getCount--) | Devuelve un número de propiedades en la colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

Agrega una propiedad a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre de la propiedad. |
| value | java.lang.String | El valor de la propiedad. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

Elimina una propiedad con el nombre especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre de la propiedad a eliminar. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

Devuelve o establece la propiedad.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad. |

**Devuelve:**
java.lang.String - Propiedad.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

Devuelve o establece la propiedad.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Devuelve la colección de nombres de propiedades. Solo lectura [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Devuelve:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```

Elimina todas las propiedades.

### getCount() {#getCount--}
```
public final int getCount()
```

Devuelve un número de propiedades en la colección. Solo lectura int.

**Devuelve:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Un java.util.Iterator para toda la colección.