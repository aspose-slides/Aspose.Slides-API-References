---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt die Zeitleiste der Animation dar.
type: docs
url: /de/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Stellt die Zeitleiste der Animation dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Gibt die Sammlung interaktiver Sequenzen zurück. |
| [getMainSequence()](#getMainSequence--) | Gibt die Hauptsequenz zurück, die nur die Haupt-Effekte-Sammlung enthalten kann. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Gibt die Sammlung von Textanimationen zurück. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


Gibt die Sammlung interaktiver Sequenzen zurück. Diese Sequenzen können nur Effekte durch „Klick auf Form“ mit angegebenem Zielobjekt enthalten. Schreibgeschützt [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Rückgabewert:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


Gibt die Hauptsequenz zurück, die nur die Haupt-Effekte-Sammlung enthalten kann. Schreibgeschützt [ISequence](../../com.aspose.slides/isequence).

**Rückgabewert:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


Gibt die Sammlung von Textanimationen zurück. Schreibgeschützt [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Rückgabewert:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)