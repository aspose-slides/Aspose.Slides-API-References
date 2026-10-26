---
title: ISequence
second_title: Aspose.Slides for Java API リファレンス
description: エフェクトのシーケンスコレクションを表します。
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

| メソッド | 説明 |
| --- | --- |
| [getCount()](#getCount--) | シーケンス内のエフェクト数を返します。 |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | コレクションから指定されたエフェクトを削除します。 |
| [removeAt(int index)](#removeAt-int-) | コレクションからエフェクトを削除します。 |
| [clear()](#clear--) | コレクションからすべてのエフェクトを削除します。 |
| [get_Item(int index)](#get-Item-int-) | 指定されたインデックスのエフェクトを返します。 |
| [getTriggerShape()](#getTriggerShape--) | INTERACTIVE シーケンスのシェイプ対象を取得または設定します。 |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | INTERACTIVE シーケンスのシェイプ対象を取得または設定します。 |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | 指定されたシェイプのエフェクトを削除します。 |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | 指定されたシェイプのエフェクト配列を返します。 |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | 指定された段落のエフェクト配列を返します。 |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | 指定されたシェイプのエフェクト数を返します。 |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | シーケンスの末尾に新しいエフェクトを追加します。 |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | シーケンスの末尾に段落用の新しいアニメーションエフェクトを追加します。 |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | シーケンスの末尾にカテゴリーまたはシリーズ用の新しいチャートアニメーションエフェクトを追加します。 |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | シーケンスの末尾にカテゴリーまたはシリーズ内の要素用の新しいチャートアニメーションエフェクトを追加します。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```

シーケンス内のエフェクト数を返します。読み取り専用 int。

**戻り値:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

コレクションから指定されたエフェクトを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | 削除するエフェクト。 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

コレクションからエフェクトを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するエフェクトのインデックス。 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect) オブジェクト。
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

INTERACTIVE シーケンスのシェイプ対象を取得または設定します。シーケンスがインタラクティブでない場合は null を返します。読み書き可能 [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

INTERACTIVE シーケンスのシェイプ対象を取得または設定します。シーケンスがインタラクティブでない場合は null を返します。読み書き可能 [IShape](../../com.aspose.slides/ishape)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

指定されたシェイプのエフェクトを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | シェイプオブジェクト [IShape](../../com.aspose.slides/ishape) |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

指定されたシェイプのエフェクト配列を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | シェイプオブジェクト [IShape](../../com.aspose.slides/ishape) |

**戻り値:**
com.aspose.slides.IEffect[] - エフェクトの配列 [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

指定された段落のエフェクト配列を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | シェイプオブジェクト [IShape](../../com.aspose.slides/ishape) |

**戻り値:**
int - エフェクトの数 int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

シーケンスの末尾に新しいエフェクトを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | エフェクト追加用のシェイプオブジェクト [IShape](../../com.aspose.slides/ishape) |
| effectType | int | アニメーションエフェクトの種類 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

シーケンスの末尾に段落用の新しいアニメーションエフェクトを追加します。

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | 段落オブジェクト [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | アニメーションエフェクトの種類 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

シーケンスの末尾にカテゴリーまたはシリーズ用の新しいチャートアニメーションエフェクトを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | チャートオブジェクト [IChart](../../com.aspose.slides/ichart) |
| type | int | アニメーションエフェクトの種類 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | インデックス int |
| effectType | int | アニメーションエフェクトの種類 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

シーケンスの末尾にカテゴリーまたはシリーズ内の要素用の新しいチャートアニメーションエフェクトを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | チャートオブジェクト [IChart](../../com.aspose.slides/ichart) |
| type | int | アニメーションエフェクトの種類 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | チャートシリーズのインデックス int |
| categoriesIndex | int | カテゴリーのインデックス int |
| effectType | int | アニメーションエフェクトの種類 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)