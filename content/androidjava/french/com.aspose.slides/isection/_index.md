---
title: ISection
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente une section de diapositives.
type: docs
url: /fr/com.aspose.slides/isection/
---```
public interface ISection
```

Représente une section de diapositives.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getName()](#getName--) | Nom de la section. |
| [setName(String value)](#setName-java.lang.String-) | Nom de la section. |
| [getSectionId()](#getSectionId--) | Identifiant de la section. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Renvoie la première diapositive de la section. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Renvoie la liste des diapositives de la section. |
### getName() {#getName--}
```
public abstract String getName()
```

Nom de la section.

**Renvoie :**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Nom de la section.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

Identifiant de la section.

**Renvoie :**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

Renvoie la première diapositive de la section.

**Renvoie :**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

Renvoie la liste des diapositives de la section.

**Renvoie :**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Liste des diapositives [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)