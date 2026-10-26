---
title: LayoutSlideCollection
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa una clase base para la colección de diapositivas de diseño.
type: docs
url: /es/com.aspose.slides/layoutslidecollection/
---
**Herencia:**  
java.lang.Object

**Todas las interfaces implementadas:**  
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject  
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Representa una clase base para la colección de diapositivas de diseño.

## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve el número de diapositivas de diseño en una colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve la diapositiva de diseño por índice. |
| [getByType(byte type)](#getByType-byte-) | Devuelve la primera diapositiva de diseño del tipo especificado. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Elimina un diseño de la colección. |
| [removeUnused()](#removeUnused--) | Elimina diapositivas de diseño no utilizadas (diapositivas de diseño cuya propiedad HasDependingSlides es false). |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

Devuelve el número de diapositivas de diseño en una colección. **Solo lectura** int.

**Devuelve:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

Devuelve la diapositiva de diseño por índice. **Solo lectura** [LayoutSlide](../../com.aspose.slides/layoutslide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

Devuelve la primera diapositiva de diseño del tipo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | byte | Un tipo de diapositiva de diseño a buscar. |

**Devuelve:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) con el tipo especificado o null si no se encuentran diseños.

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

Elimina un diseño de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | La diapositiva de diseño a eliminar de la colección. |

1) Para evitar que se lance PptxEditException, compruebe la propiedad HasDependingSlides del diseño antes. 2) También puede usar el método [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) para simplificar el código. |
---

### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

Elimina diapositivas de diseño no utilizadas (diapositivas de diseño cuya propiedad HasDependingSlides es false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Un java.util.Iterator para toda la colección.

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

Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). **Solo lectura** boolean.

**Devuelve:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. **Solo lectura** Object.

**Devuelve:**  
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. **Solo lectura** IDOMObject.

**Devuelve:**  
com.aspose.slides.IDOMObject