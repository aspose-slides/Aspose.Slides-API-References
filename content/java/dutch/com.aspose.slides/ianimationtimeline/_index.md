---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: Stelt de tijdlijn van animatie voor.
type: docs
url: /nl/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Stelt de tijdlijn van animatie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Retourneert een collectie van interactieve sequenties. |
| [getMainSequence()](#getMainSequence--) | Retourneert de hoofdsequentie die mogelijk alleen de collectie van hoofd effecten bevat. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Retourneert een collectie van tekstanimaties. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Retourneert een collectie van interactieve sequenties. Deze sequenties kunnen alleen effecten bevatten door "click on shape" met een gespecificeerde doelvorm. Alleen-lezen [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Retour:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Retourneert de hoofdsequentie die mogelijk alleen de collectie van hoofd effecten bevat. Alleen-lezen [ISequence](../../com.aspose.slides/isequence).

**Retour:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Retourneert een collectie van tekstanimaties. Alleen-lezen [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Retour:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)