---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: Represents timeline of animation.
type: docs
url: /zh-hant/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

表示動畫的時間軸。

## 方法

| Method | Description |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | 返回互動序列的集合。 |
| [getMainSequence()](#getMainSequence--) | 返回主序列，該序列可能僅包含主要效果集合。 |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | 返回文字動畫的集合。 |

### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

返回互動序列的集合。此序列可能僅包含透過「點選圖形」的效果，且指定目標圖形。唯讀 [ISequenceCollection](../../com.aspose.slides/isequencecollection)。

**返回：**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)

### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

返回主序列，該序列可能僅包含主要效果集合。唯讀 [ISequence](../../com.aspose.slides/isequence)。

**返回：**
[ISequence](../../com.aspose.slides/isequence)

### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

返回文字動畫的集合。唯讀 [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)。

**返回：**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)