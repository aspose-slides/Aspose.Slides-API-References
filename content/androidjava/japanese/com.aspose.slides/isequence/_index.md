---
title: ISequence
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: エフェクトのシーケンス コレクションを表します。
type: docs
url: /ja/com.aspose.slides/isequence/
---
**実装されているすべてのインターフェイス:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

シーケンス（エフェクトのコレクション）を表します。
## メソッド

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | シーケンス内のエフェクト数を返します。 |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | コレクションから指定されたエフェクトを削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションからエフェクトを削除します。 |
| [clear()](#clear--) | コレクションからすべてのエフェクトを削除します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのエフェクトを返します。 |
| [getTriggerShape()](#getTriggerShape--) | INTERACTIVE シーケンスのシェイプ ターゲットを取得または設定します。 |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | INTERACTIVE シーケンスのシェイプ ターゲットを取得または設定します。 |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | 指定されたシェイプのエフェクトを削除します。 |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | 指定されたシェイプのエフェクト配列を返します。 |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | 指定された段落のエフェクト配列を返します。 |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | 指定されたシェイプのエフェクト数を返します。 |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | シーケンスの末尾に新しいエフェクトを追加します。 |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | 段落の新しいアニメーションエフェクトをシーケンスの末尾に追加します。 |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | カテゴリまたはシリーズの新しいチャート アニメーション エフェクトをシーケンスの末尾に追加します。 |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | カテゴリまたはシリーズ内の要素の新しいチャート アニメーション エフェクトをシーケンスの末尾に追加します。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```

シーケンス内のエフェクト数を返します。 読み取り専用 int。

**戻り値:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

コレクションから指定されたエフェクトを削除します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | 削除するエフェクト。 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクションからエフェクトを削除します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 削除するエフェクトのインデックス int |
### clear() {#clear--}
```
public abstract void clear()
```

コレクションからすべてのエフェクトを削除します。

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

指定されたインデックスのエフェクトを返します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - The [IEffect](../../com.aspose.slides/ieffect) object.
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

INTERACTIVE シーケンスのシェイプ ターゲットを取得または設定します。 シーケンスがインタラクティブでない場合は null を返します。 読み書き [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

INTERACTIVE シーケンスのシェイプ ターゲットを取得または設定します。 シーケンスがインタラクティブでない場合は null を返します。 読み書き [IShape](../../com.aspose.slides/ishape)。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

指定されたシェイプのエフェクトを削除します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | シェイプ オブジェクト [IShape](../../com.aspose.slides/ishape) |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

指定されたシェイプのエフェクト配列を返します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | シェイプ オブジェクト [IShape](../../com.aspose.slides/ishape) |

**戻り値:**
com.aspose.slides.IEffect[] - エフェクトの配列 [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

指定された段落のエフェクト配列を返します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | 段落オブジェクト [IParagraph](../../com.aspose.slides/iparagraph) |

**戻り値:**
com.aspose.slides.IEffect[] - エフェクトの配列 [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

指定されたシェイプのエフェクト数を返します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | シェイプ オブジェクト [IShape](../../com.aspose.slides/ishape) |

**戻り値:**
int - エフェクト数 int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

シーケンスの末尾に新しいエフェクトを追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | エフェクトを追加するためのシェイプ オブジェクト [IShape](../../com.aspose.slides/ishape) |
| effectType | int | アニメーションエフェクトのタイプ [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

段落の新しいアニメーションエフェクトをシーケンスの末尾に追加します。

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // エフェクトを追加する段落を選択
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // 選択した段落にFlyアニメーションエフェクトを追加
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | 段落オブジェクト [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | アニメーションエフェクトのタイプ [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

カテゴリまたはシリーズの新しいチャート アニメーション エフェクトをシーケンスの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | チャート オブジェクト [IChart](../../com.aspose.slides/ichart) |
| type | int | アニメーションエフェクトのタイプ [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | インデックス int |
| effectType | int | アニメーションエフェクトのタイプ [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

カテゴリまたはシリーズ内の要素の新しいチャート アニメーション エフェクトをシーケンスの末尾に追加します。

**パラメータ:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | チャート オブジェクト [IChart](../../com.aspose.slides/ichart) |
| type | int | アニメーションエフェクトのタイプ [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | チャートシリーズのインデックス int |
| categoriesIndex | int | カテゴリのインデックス int |
| effectType | int | アニメーションエフェクトのタイプ [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)