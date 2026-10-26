---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Represent text animation.
type: docs
url: /ja/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

テキスト アニメーションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | 現在のシーケンスの末尾に新しいエフェクトを追加し、グループテキストアニメーションの末尾にします。 |
| [getBuildType()](#getBuildType--) | ビルドタイプのリスト（例 |
| [setBuildType(int value)](#setBuildType-int-) | ビルドタイプのリスト（例 |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | グループに属するかどうかのリンクされたシェイプエフェクト（null）。読み取り/書き込み [IEffect](../../com.aspose.slides/ieffect)。 |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | グループに属するかどうかのリンクされたシェイプエフェクト（null）。読み取り/書き込み [IEffect](../../com.aspose.slides/ieffect)。 |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

現在のシーケンスの末尾に新しいエフェクトを追加し、グループテキストアニメーションの末尾にします。このエフェクトは、テキスト段落の数がこのグループのエフェクト数以上である場合にのみ有効です！

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| effectType | int | アニメーション効果のタイプ [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーション効果のサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

テキストアニメーションのビルドタイプのリスト（例: Paragraph 1,2,3, All at Once）。読み取り/書き込み \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**戻り値:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

テキストアニメーションのビルドタイプのリスト（例: Paragraph 1,2,3, All at Once）。読み取り/書き込み \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

グループに属するかどうかのリンクされたシェイプエフェクト（null）。読み取り/書き込み [IEffect](../../com.aspose.slides/ieffect)。

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

グループに属するかどうかのリンクされたシェイプエフェクト（null）。読み取り/書き込み [IEffect](../../com.aspose.slides/ieffect)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |