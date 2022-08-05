---
title: AnimationTimeLine
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents timeline of animation.
type: docs
weight: 19
url: /java/com.aspose.slides/animationtimeline/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Represents timeline of animation.
## Methods

| Method | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Returns collection of interactive sequences. |
| [getMainSequence()](#getMainSequence--) | Returns main sequence which may contain only main effects collection. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Returns collection of text animations. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Returns collection of interactive sequences. This sequences may contain only effects by "click on shape" with specifies target shape. Read-only [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Returns:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Returns main sequence which may contain only main effects collection. Read-only [ISequence](../../com.aspose.slides/isequence).

**Returns:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Returns collection of text animations. Read-only [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Returns:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
