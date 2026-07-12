---
title: IMasterSlideCollection
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa una colección de diapositivas master.
type: docs
url: /es/com.aspose.slides/imasterslidecollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Representa una colección de diapositivas master.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Elimina la primera ocurrencia de un objeto específico de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de la colección. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Elimina las diapositivas master no utilizadas. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Añade una copia de una diapositiva master especificada al final de la colección. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Inserta una copia de una diapositiva master especificada en la posición indicada de la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo lectura [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

Elimina la primera ocurrencia de un objeto específico de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | La diapositiva master a eliminar de la colección. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina el elemento en el índice especificado de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Elimina las diapositivas master no utilizadas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ignorePreserveField | boolean | Determina si este método debe eliminar master no utilizado aunque su propiedad [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) esté establecida en true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Añade una copia de una diapositiva master especificada al final de la colección. Las diapositivas de diseño vinculadas también se copiarán.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva a clonar. |

**Devuelve:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositiva añadida.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Inserta una copia de una diapositiva master especificada en la posición indicada de la colección. Las diapositivas de diseño vinculadas también se copiarán.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la nueva diapositiva. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva a clonar. |

**Devuelve:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Diapositiva master insertada.