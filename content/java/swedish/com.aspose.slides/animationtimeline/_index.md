---
title: AnimationTimeLine
second_title: Aspose.Slides för Java API-referens
description: Representerar tidslinjen för animation.
type: docs
url: /sv/com.aspose.slides/animationtimeline/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Representerar tidslinjen för animation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Returnerar samling av interaktiva sekvenser. |
| [getMainSequence()](#getMainSequence--) | Returnerar huvudsekvensen som kan innehålla endast huvudeffektsamlingen. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Returnerar samling av textanimationer. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Returnerar samling av interaktiva sekvenser. Denna sekvens kan innehålla endast effekter genom "klicka på form" med specificerat målföremål. Skrivskyddad [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Returnerar:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Returnerar huvudsekvensen som kan innehålla endast huvudeffektsamlingen. Skrivskyddad [ISequence](../../com.aspose.slides/isequence).

**Returnerar:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Returnerar samling av textanimationer. Skrivskyddad [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Returnerar:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)