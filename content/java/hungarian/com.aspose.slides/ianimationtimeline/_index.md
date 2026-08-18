---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: Represents timeline of animation.
type: docs
url: /hu/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Az animáció idővonalát képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Visszaadja az interaktív szekvenciák gyűjteményét. |
| [getMainSequence()](#getMainSequence--) | Visszaadja a fő szekvenciát, amely csak a fő effektusok gyűjteményét tartalmazhatja. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Visszaadja a szöveges animációk gyűjteményét. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


Visszaadja az interaktív szekvenciák gyűjteményét. Ezek a szekvenciák csak a "kattintás az alakzatra" által meghatározott hatásokat tartalmazhatják a megadott célalakzattal. Csak olvasható [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Visszatér:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


Visszaadja a fő szekvenciát, amely csak a fő effektusok gyűjteményét tartalmazhatja. Csak olvasható [ISequence](../../com.aspose.slides/isequence).

**Visszatér:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


Visszaadja a szöveges animációk gyűjteményét. Csak olvasható [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Visszatér:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)