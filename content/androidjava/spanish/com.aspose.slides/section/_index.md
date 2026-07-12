---
title: Section
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa una sección de diapositivas.
type: docs
url: /es/com.aspose.slides/section/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Representa una sección de diapositivas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getName()](#getName--) | Nombre de la sección. |
| [setName(String value)](#setName-java.lang.String-) | Nombre de la sección. |
| [getSectionId()](#getSectionId--) | Id de la sección. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Devuelve la primera diapositiva de la sección. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Devuelve la lista de diapositivas de la sección. |
### getName() {#getName--}
```
public final String getName()
```


Nombre de la sección.

**Devuelve:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Nombre de la sección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


Id de la sección.

**Devuelve:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Devuelve la primera diapositiva de la sección.

**Devuelve:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Devuelve la lista de diapositivas de la sección.

**Devuelve:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lista de diapositivas.