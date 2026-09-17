---
title: ISequence class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.animation/isequence/
---
## ISequence クラス

シーケンス（エフェクトのコレクション）を表します。

ISequence型は以下のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/ja/aspose.slides.animation/isequence/count/) | シーケンス内のエフェクトの数を返します。<br/>            読み取り専用 **int**. |
| [`trigger_shape`](/slides/python-net/ja/aspose.slides.animation/isequence/trigger_shape/) | INTERACTIVEシーケンスのシェイプターゲットを取得または設定します。<br/>            シーケンスがインタラクティブでない場合はNoneを返します。<br/>            読み取り/書き込み [`IShape`](/slides/python-net/ja/aspose.slides/ishape). |

指定されたインデックスのエフェクトを返します。

## インデクサー

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.animation/isequence/__getitem__/) | インデックス |

## メソッド

| Method | Description |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/ja/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | シーケンスの末尾に新しいエフェクトを追加します。 |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/ja/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | 段落の新しいアニメーション効果をシーケンスの末尾に追加します。 |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/ja/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | カテゴリまたはシリーズの新しいチャートアニメーション効果をシーケンスの末尾に追加します。 |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/ja/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | カテゴリまたはシリーズ内の要素の新しいチャートアニメーション効果をシーケンスの末尾に追加します。 |
| [`remove(self, item)`](/slides/python-net/ja/aspose.slides.animation/isequence/remove/#ieffect) | コレクションから指定されたエフェクトを削除します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides.animation/isequence/remove_at/#int) | コレクションからエフェクトを削除します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides.animation/isequence/clear/#) | コレクションからすべてのエフェクトを削除します。 |
| [`remove_by_shape(self, shape)`](/slides/python-net/ja/aspose.slides.animation/isequence/remove_by_shape/#ishape) | 指定されたシェイプのエフェクトを削除します。 |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/ja/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | 指定されたシェイプのエフェクトの配列を返します。 |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/ja/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | 指定された段落のエフェクトの配列を返します。 |
| [`get_count(self, shape)`](/slides/python-net/ja/aspose.slides.animation/isequence/get_count/#ishape) | 指定されたシェイプのエフェクトの数を返します。 |

### 参照
* モジュール [`aspose.slides.animation`](/slides/python-net/ja/aspose.slides.animation)
* ライブラリ [`Aspose.Slides`](/slides/python-net)