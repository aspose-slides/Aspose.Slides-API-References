---
title: AnimationTimeLine
second_title: Aspose.Slides for Java API リファレンス
description: アニメーションのタイムラインを表します。
type: docs
url: /ja/com.aspose.slides/animationtimeline/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

アニメーションのタイムラインを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | インタラクティブ シーケンスのコレクションを返します。 |
| [getMainSequence()](#getMainSequence--) | メインエフェクトのコレクションのみを含む可能性があるメインシーケンスを返します。 |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | テキスト アニメーションのコレクションを返します。 |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


インタラクティブ シーケンスのコレクションを返します。このシーケンスは、指定された対象シェイプで「シェイプをクリック」することによるエフェクトのみを含む可能性があります。読み取り専用 [ISequenceCollection](../../com.aspose.slides/isequencecollection)。

**戻り値:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


メインエフェクトのコレクションのみを含む可能性があるメインシーケンスを返します。読み取り専用 [ISequence](../../com.aspose.slides/isequence)。

**戻り値:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


テキスト アニメーションのコレクションを返します。読み取り専用 [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)。

**戻り値:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)