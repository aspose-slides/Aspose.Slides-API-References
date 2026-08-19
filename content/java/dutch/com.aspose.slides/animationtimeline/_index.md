---
title: AnimationTimeLine
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de tijdlijn van animatie voor.
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

Stelt de tijdlijn van animatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Retourneert een collectie van interactieve sequenties. |
| [getMainSequence()](#getMainSequence--) | Retourneert de hoofdsequentie die alleen een collectie van hoofd-effecten kan bevatten. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Retourneert een collectie van tekstanimaties. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

Retourneert een collectie van interactieve sequenties. Deze sequenties kunnen alleen effecten bevatten die worden geactiveerd door “klik op vorm” met een opgegeven doelvorm. Alleen-lezen [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Retour:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

Retourneert de hoofdsequentie die alleen een collectie van hoofd-effecten kan bevatten. Alleen-lezen [ISequence](../../com.aspose.slides/isequence).

**Retour:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

Retourneert een collectie van tekstanimaties. Alleen-lezen [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Retour:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)