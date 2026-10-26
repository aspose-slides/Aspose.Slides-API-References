---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje časovou osu animace.
type: docs
url: /cs/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Reprezentuje časovou osu animace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Vrací kolekci interaktivních sekvencí. |
| [getMainSequence()](#getMainSequence--) | Vrací hlavní sekvenci, která může obsahovat pouze kolekci hlavních efektů. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Vrací kolekci textových animací. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Vrací kolekci interaktivních sekvencí. Tyto sekvence mohou obsahovat pouze efekty "click on shape" s určeným cílovým tvarem. Pouze pro čtení [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Vrací:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Vrací hlavní sekvenci, která může obsahovat pouze kolekci hlavních efektů. Pouze pro čtení [ISequence](../../com.aspose.slides/isequence).

**Vrací:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Vrací kolekci textových animací. Pouze pro čtení [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Vrací:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)