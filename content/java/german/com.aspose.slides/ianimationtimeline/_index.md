---
title: IAnimationTimeLine
second_title: Aspose.Slides für Java API-Referenz
description: Stellt die Zeitleiste der Animation dar.
type: docs
url: /de/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Stellt die Zeitleiste der Animation dar.
## Methoden

| Method | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Gibt Sammlung interaktiver Sequenzen zurück. |
| [getMainSequence()](#getMainSequence--) | Gibt die Hauptsequenz zurück, die nur die Sammlung der Haupteffekte enthalten kann. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Gibt Sammlung von Textanimationen zurück. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Gibt Sammlung interaktiver Sequenzen zurück. Diese Sequenzen können nur Effekte durch „Klick auf Form“ mit angegebenem Zielobjekt enthalten. Nur lesen [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Rückgabe:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Gibt die Hauptsequenz zurück, die nur die Sammlung der Haupteffekte enthalten kann. Nur lesen [ISequence](../../com.aspose.slides/isequence).

**Rückgabe:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Gibt Sammlung von Textanimationen zurück. Nur lesen [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Rückgabe:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)