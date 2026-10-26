---
title: ISection
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa una sección de diapositivas.
type: docs
url: /es/com.aspose.slides/isection/
---```
public interface ISection
```

Representa una sección de diapositivas.
## Métodos

| Method | Descripción |
| --- | --- |
| [getName()](#getName--) | Nombre de la sección. |
| [setName(String value)](#setName-java.lang.String-) | Nombre de la sección. |
| [getSectionId()](#getSectionId--) | Id de la sección. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Devuelve la primera diapositiva de la sección. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Devuelve la lista de diapositivas de la sección. |
### getName() {#getName--}
```
public abstract String getName()
```


Nombre de la sección.

**Devuelve:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Nombre de la sección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```


Id de la sección.

**Devuelve:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```


Devuelve la primera diapositiva de la sección.

**Devuelve:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


Devuelve la lista de diapositivas de la sección.

**Devuelve:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lista de diapositivas [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)