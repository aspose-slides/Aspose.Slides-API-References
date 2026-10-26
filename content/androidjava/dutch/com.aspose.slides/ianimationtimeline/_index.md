---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: Represents timeline of animation.
type: docs
url: /nl/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Stelt een tijdlijn van animatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Retourneert een verzameling van interactieve reeksen. |
| [getMainSequence()](#getMainSequence--) | Retourneert de hoofdreeks die mogelijk alleen de hoofd-effectenverzameling bevat. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Retourneert een verzameling van tekstanimaties. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Retourneert een verzameling van interactieve reeksen. Deze reeksen kunnen alleen effecten bevatten die worden geactiveerd door "klik op vorm" met een opgegeven doelvorm. Alleen-lezen [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Retourneert:**  
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Retourneert de hoofdreeks die mogelijk alleen de hoofd-effectenverzameling bevat. Alleen-lezen [ISequence](../../com.aspose.slides/isequence).

**Retourneert:**  
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Retourneert een verzameling van tekstanimaties. Alleen-lezen [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Retourneert:**  
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)