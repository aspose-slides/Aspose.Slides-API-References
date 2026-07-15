---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: 表示動畫的時間軸。
type: docs
url: /zh-hant/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

表示動畫的時間軸。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | 傳回互動序列的集合。 |
| [getMainSequence()](#getMainSequence--) | 傳回主要序列，該序列可能僅包含主要效果集合。 |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | 傳回文字動畫的集合。 |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


傳回互動序列的集合。此序列可能僅包含透過「點擊形狀」且指定目標形狀的效果。唯讀 [ISequenceCollection](../../com.aspose.slides/isequencecollection)。

**傳回：**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


傳回主要序列，該序列可能僅包含主要效果集合。唯讀 [ISequence](../../com.aspose.slides/isequence)。

**傳回：**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


傳回文字動畫的集合。唯讀 [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)。

**傳回：**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)