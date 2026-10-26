---
title: ITextAnimation
second_title: Aspose.Slides for Android via Java API Reference
description: テキストアニメーションを表します。
type: docs
url: /ja/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

テキストアニメーションを表します。

## Methods

| Method | Description |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | 現在のシーケンスの末尾に新しいエフェクトを追加して、グループテキストアニメーションの末尾にします。 |
| [getBuildType()](#getBuildType--) | ビルドタイプのリスト（例 |
| [setBuildType(int value)](#setBuildType-int-) | ビルドタイプのリスト（例 |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | グループ有無にかかわらずリンクされたシェイプエフェクト（null） 読み書き [IEffect](../../com.aspose.slides/ieffect)。 |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | グループ有無にかかわらずリンクされたシェイプエフェクト（null） 読み書き [IEffect](../../com.aspose.slides/ieffect)。 |

### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

現在のシーケンスの末尾に新しいエフェクトを追加して、グループテキストアニメーションの末尾にします。このエフェクトは、テキスト段落の数がこのグループのエフェクト数以上である場合にのみ有効です！

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| effectType | int | アニメーションエフェクトのタイプ [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returns:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)

### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

テキストアニメーションのビルドタイプのリスト（例: Paragraph 1,2,3, All at Once）。読み書き \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int)。

**Returns:**
int

### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

テキストアニメーションのビルドタイプのリスト（例: Paragraph 1,2,3, All at Once）。読み書き \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

グループ有無にかかわらずリンクされたシェイプエフェクト（null） 読み書き [IEffect](../../com.aspose.slides/ieffect)。

**Returns:**
[IEffect](../../com.aspose.slides/ieffect)

### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

グループ有無にかかわらずリンクされたシェイプエフェクト（null） 読み書き [IEffect](../../com.aspose.slides/ieffect)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |