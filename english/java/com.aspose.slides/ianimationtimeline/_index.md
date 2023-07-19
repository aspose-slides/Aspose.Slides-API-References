---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: Represents timeline of animation.
type: docs
weight: 647
url: /java/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
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
public abstract ISequenceCollection getInteractiveSequences()
```


Returns collection of interactive sequences. This sequences may contain only effects by "click on shape" with specifies target shape. Read-only [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Returns:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


Returns main sequence which may contain only main effects collection. Read-only [ISequence](../../com.aspose.slides/isequence).

**Returns:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


Returns collection of text animations. Read-only [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Returns:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
