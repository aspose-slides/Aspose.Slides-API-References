---
title: TextAnimation
second_title: Aspose.Slides for Java API リファレンス
description: テキストアニメーションを表します。
type: docs
url: /ja/com.aspose.slides/textanimation/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)  
```
public class TextAnimation implements ITextAnimation
```

テキストアニメーションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | 現在のシーケンスの末尾に新しいエフェクトを追加し、グループテキストアニメーションの末尾にします。 |
| [getBuildType()](#getBuildType--) | ビルドタイプのリスト（例）。 |
| [setBuildType(int value)](#setBuildType-int-) | ビルドタイプのリスト（例）。 |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | グループとの関連があるかどうかのシェイプ効果（null）。 |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | グループとの関連があるかどうかのシェイプ効果（null）。 |

### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

現在のシーケンスの末尾に新しいエフェクトを追加し、グループテキストアニメーションの末尾にします。このエフェクトは、テキスト段落の数がこのグループのエフェクト数と同じかそれ以上の場合にのみ有効です。

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
public final int getBuildType()
```

テキストアニメーションのビルドタイプのリスト（例：段落1、2、3、すべて同時）です。 読み取り/書き込み [BuildType](../../com.aspose.slides/buildtype)。

**戻り値:**
int

### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

ビルドタイプのリスト（例：段落1、2、3、すべて同時）です。 読み取り/書き込み [BuildType](../../com.aspose.slides/buildtype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

グループとの関連があるかどうかのシェイプ効果（null）。 読み取り/書き込み [IEffect](../../com.aspose.slides/ieffect)。

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

グループとの関連があるかどうかのシェイプ効果（null）。 読み取り/書き込み [IEffect](../../com.aspose.slides/ieffect)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |