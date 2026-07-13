---
title: AnimationTimeLine
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een tijdlijn van animatie voor.
type: docs
url: /nl/com.aspose.slides/animationtimeline/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Stelt een tijdlijn van animatie voor.
## Methoden

| Method | Beschrijving |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Retourneert een collectie van interactieve volgordes. |
| [getMainSequence()](#getMainSequence--) | Retourneert de hoofdvolgorde die mogelijk alleen een collectie van hoofd-effecten bevat. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Retourneert een collectie van tekstanimaties. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Retourneert een collectie van interactieve volgordes. Deze volgordes kunnen alleen effect bevatten door "klik op vorm" met een gespecificeerde doelvorm. Alleen-lezen [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Retour:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Retourneert de hoofdvolgorde die mogelijk alleen een collectie van hoofd-effecten bevat. Alleen-lezen [ISequence](../../com.aspose.slides/isequence).

**Retour:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Retourneert een collectie van tekstanimaties. Alleen-lezen [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Retour:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)