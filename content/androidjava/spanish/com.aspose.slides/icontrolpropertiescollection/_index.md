---
title: IControlPropertiesCollection
second_title: Referencia de API de Java de Aspose.Slides para Android
description: Una colección de controles ActiveX.
type: docs
url: /es/com.aspose.slides/icontrolpropertiescollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Una colección de controles ActiveX.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Devuelve un número de propiedades en la colección. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Agrega una propiedad a la colección. |
| [remove(String name)](#remove-java.lang.String-) | Elimina una propiedad con el nombre especificado. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Devuelve o establece la propiedad. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Devuelve o establece la propiedad. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Devuelve un número de propiedades en la colección. |
| [clear()](#clear--) | Elimina todas las propiedades. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Devuelve un número de propiedades en la colección. Solo lectura int.

**Devuelve:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

Agrega una propiedad a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre de la propiedad. |
| value | java.lang.String | El valor de la propiedad. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Elimina una propiedad con el nombre especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | El nombre de la propiedad a eliminar. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```

Devuelve o establece la propiedad.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la propiedad. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

Devuelve un número de propiedades en la colección. Solo lectura [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Devuelve:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

Elimina todas las propiedades.