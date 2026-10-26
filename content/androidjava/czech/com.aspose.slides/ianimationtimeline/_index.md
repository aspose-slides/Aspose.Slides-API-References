---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje časovou osu animace.
type: docs
url: /cs/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Reprezentuje časovou osu animace.
## Methods

| Metoda | Popis |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Vrací kolekci interaktivních sekvencí. |
| [getMainSequence()](#getMainSequence--) | Vrací hlavní sekvenci, která může obsahovat pouze kolekci hlavních efektů. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Vrací kolekci textových animací. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Vrací kolekci interaktivních sekvencí. Tyto sekvence mohou obsahovat pouze efekty „kliknutí na tvar“ s určeným cílovým tvarem. Pouze pro čtení [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Returns:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Vrací hlavní sekvenci, která může obsahovat pouze kolekci hlavních efektů. Pouze pro čtení [ISequence](../../com.aspose.slides/isequence).

**Returns:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Vrací kolekci textových animací. Pouze pro čtení [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Returns:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)