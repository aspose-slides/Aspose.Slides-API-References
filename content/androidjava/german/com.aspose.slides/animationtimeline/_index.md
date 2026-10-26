---
title: AnimationTimeLine
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt die Zeitleiste der Animation dar.
type: docs
url: /de/com.aspose.slides/animationtimeline/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Stellt die Zeitleiste der Animation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Gibt eine Sammlung interaktiver Sequenzen zurück. |
| [getMainSequence()](#getMainSequence--) | Gibt die Hauptsequenz zurück, die nur die Sammlung der Haupteffekte enthalten kann. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Gibt eine Sammlung von Textanimationen zurück. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Gibt eine Sammlung interaktiver Sequenzen zurück. Diese Sequenzen können nur Effekte durch "click on shape" mit einem angegebenen Zielobjekt enthalten. Nur lesbar [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Rückgabe:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Gibt die Hauptsequenz zurück, die nur die Sammlung der Haupteffekte enthalten kann. Nur lesbar [ISequence](../../com.aspose.slides/isequence).

**Rückgabe:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Gibt eine Sammlung von Textanimationen zurück. Nur lesbar [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Rückgabe:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)