---
title: TextAnimation
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: テキスト アニメーションを表します。
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

テキスト アニメーションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | 現在のシーケンスの最後に新しいエフェクトを追加し、グループ テキスト アニメーションの最後に配置します。 |
| [getBuildType()](#getBuildType--) | ビルドタイプのリスト（例 |
| [setBuildType(int value)](#setBuildType-int-) | ビルドタイプのリスト（例 |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | グループがあるかどうかにかかわらずリンクされたシェイプ エフェクト（null）。 |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | グループがあるかどうかにかかわらずリンクされたシェイプ エフェクト（null）。 |

### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```

現在のシーケンスの最後に新しいエフェクトを追加し、グループ テキスト アニメーションの最後に配置します。このエフェクトは、テキスト段落の数がこのグループのエフェクト数以上である場合にのみ有効です！

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| effectType | int | アニメーション エフェクトのタイプ [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーション エフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガー タイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクト オブジェクト [IEffect](../../com.aspose.slides/ieffect)

### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```

テキスト アニメーションのビルドタイプのリスト（例: Paragraph 1,2,3, All at Once）。読み取り/書き込み [BuildType](../../com.aspose.slides/buildtype)。

**戻り値:**
int

### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```

テキスト アニメーションのビルドタイプのリスト（例: Paragraph 1,2,3, All at Once）。読み取り/書き込み [BuildType](../../com.aspose.slides/buildtype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```

グループがあるかどうかにかかわらずリンクされたシェイプ エフェクト（null）。読み取り/書き込み [IEffect](../../com.aspose.slides/ieffect)。

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```

グループがあるかどうかにかかわらずリンクされたシェイプ エフェクト（null）。読み取り/書き込み [IEffect](../../com.aspose.slides/ieffect)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |