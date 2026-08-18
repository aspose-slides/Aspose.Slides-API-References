---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: アニメーションのタイムラインを表します。
type: docs
url: /ja/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

アニメーションのタイムラインを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | インタラクティブ シーケンスのコレクションを返します。 |
| [getMainSequence()](#getMainSequence--) | メイン効果コレクションのみを含む可能性があるメインシーケンスを返します。 |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | テキストアニメーションのコレクションを返します。 |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


インタラクティブ シーケンスのコレクションを返します。このシーケンスは「シェイプのクリック」によって指定されたターゲット シェイプのみを含む可能性があります。読み取り専用 [ISequenceCollection](../../com.aspose.slides/isequencecollection)。

**戻り値:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


メイン効果コレクションのみを含む可能性があるメインシーケンスを返します。読み取り専用 [ISequence](../../com.aspose.slides/isequence)。

**戻り値:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


テキストアニメーションのコレクションを返します。読み取り専用 [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)。

**戻り値:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)