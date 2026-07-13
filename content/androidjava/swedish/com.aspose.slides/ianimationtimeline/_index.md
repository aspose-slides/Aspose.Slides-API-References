---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar tidslinjen för animation.
type: docs
url: /sv/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Representerar tidslinjen för animation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Returnerar en samling av interaktiva sekvenser. |
| [getMainSequence()](#getMainSequence--) | Returnerar huvudsekvensen som kan innehålla endast huvudeffektsamlingen. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Returnerar en samling av textanimationer. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


Returnerar en samling av interaktiva sekvenser. Denna sekvens kan endast innehålla effekter genom "klicka på form" med specificerad målform. Skrivskyddad [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Returnerar:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


Returnerar huvudsekvensen som kan innehålla endast huvudeffektsamlingen. Skrivskyddad [ISequence](../../com.aspose.slides/isequence).

**Returnerar:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


Returnerar en samling av textanimationer. Skrivskyddad [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Returnerar:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)