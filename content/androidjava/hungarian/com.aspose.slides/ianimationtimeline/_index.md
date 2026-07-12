---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android Java API hivatkozás
description: Az animáció idővonalát képviseli.
type: docs
url: /hu/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Az animáció idővonalát képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Visszaadja az interaktív szekvenciák gyűjteményét. |
| [getMainSequence()](#getMainSequence--) | Visszaadja a fő szekvenciát, amely csak a fő hatások gyűjteményét tartalmazhatja. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Visszaadja a szöveganimációk gyűjteményét. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Visszaadja az interaktív szekvenciák gyűjteményét. Ezek a szekvenciák csak a "click on shape" hatásokat tartalmazhatják a megadott célformával. Csak olvasható [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Visszatér:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Visszaadja a fő szekvenciát, amely csak a fő hatások gyűjteményét tartalmazhatja. Csak olvasható [ISequence](../../com.aspose.slides/isequence).

**Visszatér:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Visszaadja a szöveganimációk gyűjteményét. Csak olvasható [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Visszatér:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)