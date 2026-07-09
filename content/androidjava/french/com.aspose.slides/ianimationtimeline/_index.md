---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: Représente la chronologie de l'animation.
type: docs
url: /fr/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Représente la chronologie de l'animation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Renvoie la collection de séquences interactives. |
| [getMainSequence()](#getMainSequence--) | Renvoie la séquence principale qui peut contenir uniquement la collection d'effets principaux. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Renvoie la collection d'animations de texte. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Renvoie la collection de séquences interactives. Ces séquences peuvent contenir uniquement des effets déclenchés par « cliquer sur la forme » avec la forme cible spécifiée. Lecture seule [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Renvoie:**  
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Renvoie la séquence principale qui peut contenir uniquement la collection d'effets principaux. Lecture seule [ISequence](../../com.aspose.slides/isequence).

**Renvoie:**  
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Renvoie la collection d'animations de texte. Lecture seule [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Renvoie:**  
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)