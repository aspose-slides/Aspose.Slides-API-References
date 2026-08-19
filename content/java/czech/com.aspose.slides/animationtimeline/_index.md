---
title: AnimationTimeLine
second_title: Aspose.Slides pro Java API Reference
description: Představuje časovou osu animace.
type: docs
url: /cs/com.aspose.slides/animationtimeline/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Představuje časovou osu animace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Vrací kolekci interaktivních sekvencí. |
| [getMainSequence()](#getMainSequence--) | Vrací hlavní sekvenci, která může obsahovat pouze kolekci hlavních efektů. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Vrací kolekci textových animací. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

Vrací kolekci interaktivních sekvencí. Tato sekvence může obsahovat pouze efekty pomocí "click on shape" s určeným cílovým tvarem. Pouze ke čtení [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Vrací:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

Vrací hlavní sekvenci, která může obsahovat pouze kolekci hlavních efektů. Pouze ke čtení [ISequence](../../com.aspose.slides/isequence).

**Vrací:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

Vrací kolekci textových animací. Pouze ke čtení [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Vrací:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)