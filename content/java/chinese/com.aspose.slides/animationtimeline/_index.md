---
title: AnimationTimeLine
second_title: Aspose.Slides for Java API 参考
description: 表示动画时间线。
type: docs
url: /zh/com.aspose.slides/animationtimeline/
---
**继承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**  
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)  
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

表示动画时间线。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | 返回交互序列的集合。 |
| [getMainSequence()](#getMainSequence--) | 返回可能仅包含主效果集合的主序列。 |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | 返回文本动画的集合。 |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

返回交互序列的集合。此序列可能仅包含通过“click on shape”指定目标形状的效果。只读 [ISequenceCollection](../../com.aspose.slides/isequencecollection)。

**返回:**  
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

返回可能仅包含主效果集合的主序列。只读 [ISequence](../../com.aspose.slides/isequence)。

**返回:**  
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

返回文本动画的集合。只读 [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)。

**返回:**  
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)