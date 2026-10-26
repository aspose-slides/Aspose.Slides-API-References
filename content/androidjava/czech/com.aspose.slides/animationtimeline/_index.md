---
title: AnimationTimeLine
second_title: Aspose.Slides pro Android prostřednictvím Java API
description: Reprezentuje časovou osu animace.
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
| [getMainSequence()](#getMainSequence--) | Vrací hlavní sekvenci, která může obsahovat pouze hlavní kolekci efektů. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Vrací kolekci textových animací. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Vrací kolekci interaktivních sekvencí. Tyto sekvence mohou obsahovat pouze efekty "kliknutí na tvar" s určeným cílovým tvarem. Pouze pro čtení [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Vrací:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Vrací hlavní sekvenci, která může obsahovat pouze hlavní kolekci efektů. Pouze pro čtení [ISequence](../../com.aspose.slides/isequence).

**Vrací:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Vrací kolekci textových animací. Pouze pro čtení [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Vrací:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)