---
title: Section
second_title: Référence API Aspose.Slides pour Java
description: Représente une section de diapositives.
type: docs
url: /fr/com.aspose.slides/section/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Représente une section de diapositives.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Nom de la section. |
| [setName(String value)](#setName-java.lang.String-) | Nom de la section. |
| [getSectionId()](#getSectionId--) | ID de la section. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Renvoie la première diapositive de la section. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Renvoie la liste des diapositives de la section. |
### getName() {#getName--}
```
public final String getName()
```


Nom de la section.

**Retourne:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Nom de la section.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


ID de la section.

**Retourne:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Renvoie la première diapositive de la section.

**Retourne:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Renvoie la liste des diapositives de la section.

**Retourne:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Liste des diapositives.