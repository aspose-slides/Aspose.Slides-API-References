---
title: Sequence
second_title: Aspose.Slides for Java API リファレンス
description: エフェクトのシーケンスコレクションを表します。
type: docs
url: /ja/com.aspose.slides/sequence/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
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
| [iterator()](#iterator--) | コレクションを反復する列挙子を返します。 |
| [iteratorJava()](#iteratorJava--) | コレクション全体の Java イテレータを返します。 |
| [getTriggerShape()](#getTriggerShape--) | INTERACTIVE シーケンスのシェイプ対象を取得または設定します。 |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | INTERACTIVE シーケンスのシェイプ対象を取得または設定します。 |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | 指定されたシェイプのエフェクトを削除します。 |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | 指定されたシェイプのエフェクト配列を返します。 |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | 指定されたパラグラフのエフェクト配列を返します。 |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | 指定されたシェイプのエフェクト数を返します。 |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | シーケンスの末尾に新しいエフェクトを追加します。 |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | パラグラフの新しいアニメーションエフェクトをシーケンスの末尾に追加します。 |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | カテゴリまたは系列の新しいチャートアニメーションエフェクトをシーケンスの末尾に追加します。 |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | カテゴリまたは系列内の要素の新しいチャートアニメーションエフェクトをシーケンスの末尾に追加します。 |

### getCount() {#getCount--}
```
public final int getCount()
```

シーケンス内のエフェクト数を返します。読み取り専用 int。

**戻り値:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

コレクションから指定されたエフェクトを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | 削除するエフェクト。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

コレクションからエフェクトを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 削除するエフェクトのインデックス。 |

### clear() {#clear--}
```
public final void clear()
```

コレクションからすべてのエフェクトを削除します。

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

指定されたインデックスのエフェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 要素のインデックス。 |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect) オブジェクト。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

コレクションを反復する列挙子を返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - コレクションを反復できる IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

コレクション全体の Java イテレータを返します。

**戻り値:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - コレクション全体の java.util.Iterator。

### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

INTERACTIVE シーケンスのシェイプ対象を取得または設定します。シーケンスがインタラクティブでない場合は null を返します。読み取り/書き込み [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

INTERACTIVE シーケンスのシェイプ対象を取得または設定します。シーケンスがインタラクティブでない場合は null を返します。読み取り/書き込み [IShape](../../com.aspose.slides/ishape)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

指定されたシェイプのエフェクトを削除します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

指定されたシェイプのエフェクト配列を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**戻り値:**
com.aspose.slides.IEffect[]

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

指定されたパラグラフのエフェクト配列を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**戻り値:**
com.aspose.slides.IEffect[]

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

指定されたシェイプのエフェクト数を返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**戻り値:**
int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

シーケンスの末尾に新しいエフェクトを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | エフェクトを追加する対象シェイプオブジェクト [IShape](../../com.aspose.slides/ishape) |
| effectType | int | アニメーションエフェクトの種類 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

パラグラフの新しいアニメーションエフェクトをシーケンスの末尾に追加します。

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // エフェクトを追加する段落を選択
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // 選択した段落にFlyアニメーション効果を追加
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | パラグラフオブジェクト [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | アニメーションエフェクトの種類 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

カテゴリまたは系列の新しいチャートアニメーションエフェクトをシーケンスの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | チャートオブジェクト [IChart](../../com.aspose.slides/ichart) |
| type | int | アニメーションエフェクトの種類 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | インデックス |
| effectType | int | アニメーションエフェクトの種類 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

カテゴリまたは系列内の要素の新しいチャートアニメーションエフェクトをシーケンスの末尾に追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | チャートオブジェクト [IChart](../../com.aspose.slides/ichart) |
| type | int | アニメーションエフェクトの種類 [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | チャート系列のインデックス |
| categoriesIndex | int | カテゴリのインデックス |
| effectType | int | アニメーションエフェクトの種類 [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | アニメーションエフェクトのサブタイプ [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | エフェクトのトリガータイプ [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**戻り値:**
[IEffect](../../com.aspose.slides/ieffect) - 新しいエフェクトオブジェクト [IEffect](../../com.aspose.slides/ieffect)