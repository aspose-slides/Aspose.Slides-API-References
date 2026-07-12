---
title: AdjustValueCollection
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa una colección de ajustes de formas.
type: docs
url: /es/com.aspose.slides/adjustvaluecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

Representa una colección de ajustes de forma.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve un número de ajustes. |
| [get_Item(int index)](#get-Item-int-) | Devuelve el ajuste por índice. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve la raíz de sincronización. |
| [iterator()](#iterator--) | Devuelve un enumerador para toda la colección. |
### size() {#size--}
```
public final int size()
```

Devuelve un número de ajustes. int de solo lectura.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

Devuelve el ajuste por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | índice del ajuste. |

**Devuelve:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice de inicio en el array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). boolean de solo lectura.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve la raíz de sincronización. Object de solo lectura.

**Devuelve:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

Devuelve un enumerador para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.IEnumerator