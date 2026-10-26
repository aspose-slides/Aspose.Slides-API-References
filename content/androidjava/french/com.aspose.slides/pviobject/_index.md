---
title: PVIObject
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Encapsule l'infrastructure de service de base pour les objets pouvant être soumis à l'héritage de la valeur d'une propriété.
type: docs
url: /fr/com.aspose.slides/pviobject/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Encapsule l’infrastructure de service de base pour les objets pouvant être sujets à l’héritage de la valeur d’une propriété.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Compare avec l'objet spécifié. |
| [hashCode()](#hashCode--) | Renvoie le code de hachage. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Lecture seule long.

**Renvoie :**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

Renvoie le parent IPresentationComponent. Lecture seule [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Renvoie :**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**Renvoie :**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

Renvoie la diapositive de base. Lecture seule [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Renvoie :**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Renvoie la présentation. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Compare avec l'objet spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Objet à comparer. |

**Renvoie :**
boolean - Vrai si les objets sont égaux, sinon faux.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Renvoie le code de hachage.

**Renvoie :**
int - Code de hachage.