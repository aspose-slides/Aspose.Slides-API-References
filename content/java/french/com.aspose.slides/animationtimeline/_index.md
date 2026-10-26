---
title: AnimationTimeLine
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente la chronologie de l'animation.
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

Représente la chronologie de l'animation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Renvoie une collection de séquences interactives. |
| [getMainSequence()](#getMainSequence--) | Renvoie la séquence principale qui ne peut contenir que la collection d'effets principaux. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Renvoie une collection d'animations de texte. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

Renvoie une collection de séquences interactives. Ces séquences peuvent ne contenir que des effets déclenchés par "clic sur la forme" avec une forme cible spécifiée. Lecture seule [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Renvoie:**  
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

Renvoie la séquence principale qui ne peut contenir que la collection d'effets principaux. Lecture seule [ISequence](../../com.aspose.slides/isequence).

**Renvoie:**  
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

Renvoie une collection d'animations de texte. Lecture seule [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Renvoie:**  
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)