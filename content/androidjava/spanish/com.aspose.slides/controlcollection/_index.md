---
title: ControlCollection
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Una colección de controles ActiveX.
type: docs
url: /es/com.aspose.slides/controlcollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Una colección de controles ActiveX.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve un número de objetos en la colección. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Crea y agrega un nuevo control a la colección. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Elimina un control ActiveX de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina un control ActiveX almacenado en la posición especificada de la colección. |
| [clear()](#clear--) | Elimina todos los controles de la colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve un control en la posición especificada. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia toda la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve un origen de sincronización. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Devuelve un número de objetos en la colección. Solo lectura int.

**Devuelve:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Crea y agrega un nuevo control a la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| controlType | int | Tipo de control a agregar. |
| x | float | La coordenada X del lado izquierdo del marco de la forma. |
| y | float | La coordenada Y del lado superior del marco de la forma. |
| width | float | El ancho del marco de la forma. |
| height | float | La altura del marco de la forma. |

**Devuelve:**
[IControl](../../com.aspose.slides/icontrol) - Control creado.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Elimina un control ActiveX de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Un control a eliminar. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina un control ActiveX almacenado en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del control a eliminar. |

### clear() {#clear--}
```
public final void clear()
```

Elimina todos los controles de la colección.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Devuelve un control en la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de un control. |

**Devuelve:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia toda la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino |
| index | int | Índice en el array de destino. |

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

Devuelve un origen de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject