---
title: MasterSlideCollection
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa una colección de master slides.
type: docs
url: /es/com.aspose.slides/masterslidecollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Representa una colección de master slides.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Elimina la primera aparición de un objeto específico de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Elimina master slides no usados. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Añade una copia de un master slide especificado al final de la colección. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Inserta una copia de un master slide especificado en la posición indicada de la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al array especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### size() {#size--}
```
public final int size()
```

Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo lectura [MasterSlide](../../com.aspose.slides/masterslide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

Elimina la primera aparición de un objeto específico de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | El master slide a eliminar de la colección. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina el elemento en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

--------------------

Para evitar lanzar la PptxEditException, compruebe la propiedad HasDependingSlides del master antes.

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Elimina master slides no usados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ignorePreserveField | boolean | Determina si este método debe eliminar master sin usar incluso si su propiedad [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) está establecida en true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

Añade una copia de un master slide especificado al final de la colección. Las diapositivas de diseño vinculadas también se copiarán.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva a clonar. |

**Devuelve:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositiva añadida.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Inserta una copia de un master slide especificado en la posición indicada de la colección. Las diapositivas de diseño vinculadas también se copiarán.

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Instanciar la clase Presentation para cargar el archivo de presentación origen
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Instanciar la clase Presentation para la presentación de destino (donde se clonará la diapositiva)
>      Presentation destPres = new Presentation();
>      try {
>          // Instanciar ISlide a partir de la colección de diapositivas en la presentación origen junto con
>          // Diapositiva maestra
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Obtener las diapositivas maestras de la presentación de destino
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Clonar la diapositiva maestra deseada de la presentación origen a la colección de maestras en la
>          // presentación de destino
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Colección de diapositivas en la presentación de destino
>          ISlideCollection slds = destPres.getSlides();
>          // Clonar la diapositiva origen a la colección de diapositivas de destino.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Guardar la presentación de destino en disco
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la nueva diapositiva. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva a clonar. |

**Devuelve:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Master slide insertada.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al array especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial en el array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (thread-safe). Solo lectura boolean.

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
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Un java.util.Iterator para toda la colección.