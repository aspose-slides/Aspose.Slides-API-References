---
title: AnimationTimeLine
second_title: Aspose.Slides Java API hivatkozás
description: Az animáció idővonalát reprezentálja.
type: docs
url: /hu/com.aspose.slides/animationtimeline/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Az összes megvalósított interfész:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Az animáció idővonalát reprezentálja.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Visszaadja a interaktív szekvenciák gyűjteményét. |
| [getMainSequence()](#getMainSequence--) | Visszaadja a fő szekvenciát, amely csak a fő hatások gyűjteményét tartalmazhatja. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Visszaadja a szöveganimációk gyűjteményét. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Visszaadja a interaktív szekvenciák gyűjteményét. Ez a szekvencia csak a "click on shape" hatásokat tartalmazhatja, a megadott célformával. Csak olvasható [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Visszatérési érték:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Visszaadja a fő szekvenciát, amely csak a fő hatások gyűjteményét tartalmazhatja. Csak olvasható [ISequence](../../com.aspose.slides/isequence).

**Visszatérési érték:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Visszaadja a szöveganimációk gyűjteményét. Csak olvasható [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Visszatérési érték:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)