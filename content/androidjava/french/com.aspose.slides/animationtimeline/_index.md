---
title: AnimationTimeLine
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Représente la chronologie d'une animation.
type: docs
url: /fr/com.aspose.slides/animationtimeline/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Représente la chronologie d'une animation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Renvoie une collection de séquences interactives. |
| [getMainSequence()](#getMainSequence--) | Renvoie la séquence principale qui ne peut contenir que la collection des effets principaux. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Renvoie une collection d'animations de texte. |

### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

Renvoie une collection de séquences interactives. Ces séquences ne peuvent contenir que des effets déclenchés par "cliquer sur la forme" avec une forme cible spécifiée. Lecture seule [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Retour :**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)

### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

Renvoie la séquence principale qui ne peut contenir que la collection des effets principaux. Lecture seule [ISequence](../../com.aspose.slides/isequence).

**Retour :**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

Renvoie une collection d'animations de texte. Lecture seule [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Retour :**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)