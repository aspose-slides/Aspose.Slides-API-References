---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa una colección de esquemas de color adicionales.
type: docs
url: /es/com.aspose.slides/extracolorschemecollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Representa una colección de esquemas de color adicionales.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve un número de elementos int en la colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve un esquema de color por índice. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso al ArrayList está sincronizado (seguro para hilos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve un objeto que puede usarse para sincronizar el acceso a la colección. |
### size() {#size--}
```
public final int size()
```

Devuelve un número de elementos int en la colección. Solo lectura int.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

Devuelve un esquema de color por índice. Solo lectura [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - Un java.util.Iterator para toda la colección.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial en el array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso al ArrayList está sincronizado (seguro para hilos). Solo lectura boolean.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve un objeto que puede usarse para sincronizar el acceso a la colección. Solo lectura Object.

Devuelve una raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object