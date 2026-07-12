---
title: ISectionCollection
second_title: Referencia de API de Java para Aspose.Slides en Android
description: Representa una colección de secciones.
type: docs
url: /es/com.aspose.slides/isectioncollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Representa una colección de secciones.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Añade una nueva sección iniciada a partir de una diapositiva específica. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Añade una sección vacía en la posición especificada de la colección. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Elimina la sección y las diapositivas que contiene. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Elimina la sección. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Mueve la sección y sus diapositivas de la colección a la posición especificada. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Añade una sección vacía al final de la colección. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Devuelve un índice de la sección especificada en la colección. |
| [clear()](#clear--) | Elimina todas las secciones de la colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
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
public abstract ISection addSection(String name, ISlide startedFromSlide)
```

Añade una nueva sección iniciada a partir de una diapositiva específica.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la sección |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Primera diapositiva de la sección |

**Devuelve:**
[ISection](../../com.aspose.slides/isection) - Sección añadida.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```

Añade una sección vacía en la posición especificada de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la sección |
| index | int | Índice de la nueva sección. |

**Devuelve:**
[ISection](../../com.aspose.slides/isection) - Sección añadida.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```

Elimina la sección y las diapositivas que contiene.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La sección a eliminar de la colección. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Elimina la sección. Las diapositivas contenidas en la sección se fusionarán con la sección anterior.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La sección a eliminar de la colección. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Mueve la sección y sus diapositivas de la colección a la posición especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sección a mover. |
| index | int | Índice de destino. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Añade una sección vacía al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | java.lang.String | Nombre de la sección |

**Devuelve:**
[ISection](../../com.aspose.slides/isection) - Sección añadida.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```

Devuelve un índice de la sección especificada en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sección a buscar. |

**Devuelve:**
int - Índice de una sección o -1 si la sección no pertenece a esta colección.
### clear() {#clear--}
```
public abstract void clear()
```

Elimina todas las secciones de la colección.