---
title: AnimationTimeLine
second_title: Aspose.Slides Androidhoz Java API referencia
description: Az animáció idővonalát képviseli.
type: docs
url: /hu/com.aspose.slides/animationtimeline/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Az animáció idővonalát képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Visszaadja az interaktív szekvenciák gyűjteményét. |
| [getMainSequence()](#getMainSequence--) | Visszaadja a fő szekvenciát, amely csak a fő hatások gyűjteményét tartalmazhat. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Visszaadja a szöveges animációk gyűjteményét. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

Visszaadja az interaktív szekvenciák gyűjteményét. Ez a szekvencia csak a "kattintás az alakzatra" hatásokat tartalmazhat a meghatározott célalakzattal. Csak olvasható [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Visszatér:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

Visszaadja a fő szekvenciát, amely csak a fő hatások gyűjteményét tartalmazhat. Csak olvasható [ISequence](../../com.aspose.slides/isequence).

**Visszatér:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

Visszaadja a szöveg animációk gyűjteményét. Csak olvasható [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Visszatér:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)