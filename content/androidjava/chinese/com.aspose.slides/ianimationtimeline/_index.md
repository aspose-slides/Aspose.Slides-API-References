---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: 表示动画的时间线。
type: docs
url: /zh/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

表示动画的时间线。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | 返回交互序列的集合。 |
| [getMainSequence()](#getMainSequence--) | 返回主序列，可能仅包含主要效果集合。 |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | 返回文本动画的集合。 |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

返回交互序列的集合。此序列可能仅包含通过“单击形状”指定目标形状的效果。只读 [ISequenceCollection](../../com.aspose.slides/isequencecollection)。

**返回：**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

返回主序列，可能仅包含主要效果集合。只读 [ISequence](../../com.aspose.slides/isequence)。

**返回：**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

返回文本动画的集合。只读 [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)。

**返回：**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)