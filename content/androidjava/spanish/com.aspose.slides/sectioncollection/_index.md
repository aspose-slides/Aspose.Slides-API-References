---
title: SectionCollection
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa una colección de secciones.
type: docs
url: /es/com.aspose.slides/sectioncollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Representa una colección de secciones.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Agrega una sección de diapositivas que comienza desde una diapositiva específica. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Agrega una sección vacía al final de la colección. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Agrega una sección vacía en la posición especificada de la colección. |
| [size()](#size--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Devuelve el índice de la sección especificada en la colección. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Elimina la sección y las diapositivas contenidas en ella. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Elimina la sección. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Mueve la sección y sus diapositivas de la colección a la posición especificada. |
| [clear()](#clear--) | Elimina todas las secciones de la colección. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia toda la colección al arreglo especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve la raíz de sincronización. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo lectura [ISection](../../com.aspose.slides/isection).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Agrega una sección de diapositivas que comienza desde una diapositiva específica.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la sección |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Primera diapositiva de la sección |

**Devuelve:**
[ISection](../../com.aspose.slides/isection) - Sección agregada.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Agrega una sección vacía al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la sección |

**Devuelve:**
[ISection](../../com.aspose.slides/isection) - Sección agregada.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Agrega una sección vacía en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la sección |
| index | int | Índice de la nueva sección. |

**Devuelve:**
[ISection](../../com.aspose.slides/isection) - Sección agregada.
### size() {#size--}
```
public final int size()
```

Obtiene el número de elementos realmente contenidos en la colección. Solo lectura int.

**Devuelve:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Devuelve el índice de la sección especificada en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sección a encontrar. |

**Devuelve:**
int - Índice de una sección o -1 si la sección no pertenece a esta colección.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Elimina la sección y las diapositivas contenidas en ella.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La sección a eliminar de la colección. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Elimina la sección. Las diapositivas contenidas en la sección se fusionarán con la sección anterior.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La sección a eliminar de la colección. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Mueve la sección y sus diapositivas de la colección a la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sección a mover. |
| index | int | Índice objetivo. |

### clear() {#clear--}
```
public final void clear()
```

Elimina todas las secciones de la colección.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia toda la colección al arreglo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Arreglo objetivo |
| index | int | Índice en el arreglo objetivo. |

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

Devuelve la raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Un java.util.Iterator para toda la colección.