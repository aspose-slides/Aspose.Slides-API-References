---
title: AnimationTimeLine
second_title: Aspose.Slides for Android Java API 參考
description: 表示動畫的時間軸。
type: docs
url: /zh-hant/com.aspose.slides/animationtimeline/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

表示動畫的時間軸。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | 傳回互動序列的集合。 |
| [getMainSequence()](#getMainSequence--) | 傳回主序列，可能僅包含主要效果集合。 |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | 傳回文字動畫的集合。 |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```

傳回互動序列的集合。此序列可能只包含透過「點擊形狀」指定目標形狀的效果。唯讀 [ISequenceCollection](../../com.aspose.slides/isequencecollection)。

**返回：**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```

傳回主序列，可能僅包含主要效果集合。唯讀 [ISequence](../../com.aspose.slides/isequence)。

**返回：**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```

傳回文字動畫的集合。唯讀 [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)。

**返回：**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)