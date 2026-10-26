---
title: Sequence class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.animation/sequence/
---
## Sequence クラス

シーケンス（エフェクトのコレクション）を表します。

Sequence 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`count`](/slides/python-net/ja/aspose.slides.animation/sequence/count/) | シーケンス内のエフェクト数を返します。<br/>            読み取り専用 **int**. |
| [`trigger_shape`](/slides/python-net/ja/aspose.slides.animation/sequence/trigger_shape/) | INTERACTIVE シーケンスのシェイプターゲットを取得または設定します。<br/>            シーケンスがインタラクティブでない場合は None を返します。<br/>            読み取り/書き込み [`IShape`](/slides/python-net/ja/aspose.slides/ishape). |

指定されたインデックスのエフェクトを返します。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.animation/sequence/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/ja/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | シーケンスの末尾に新しいエフェクトを追加します。 |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/ja/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | シーケンスの末尾に段落用の新しいアニメーションエフェクトを追加します。 |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/ja/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | シーケンスの末尾にカテゴリまたはシリーズ用の新しいチャートアニメーションエフェクトを追加します。 |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/ja/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | シーケンスの末尾にカテゴリまたはシリーズ内の要素用の新しいチャートアニメーションエフェクトを追加します。 |
| [`remove(self, item)`](/slides/python-net/ja/aspose.slides.animation/sequence/remove/#ieffect) | コレクションから指定されたエフェクトを削除します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides.animation/sequence/remove_at/#int) | コレクションからエフェクトを削除します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides.animation/sequence/clear/#) | コレクションからすべてのエフェクトを削除します。 |
| [`remove_by_shape(self, shape)`](/slides/python-net/ja/aspose.slides.animation/sequence/remove_by_shape/#ishape) | 指定されたシェイプのエフェクトを削除します。 |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/ja/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | 指定されたシェイプのエフェクト配列を返します。 |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/ja/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | 指定された段落のエフェクト配列を返します。 |
| [`get_count(self, shape)`](/slides/python-net/ja/aspose.slides.animation/sequence/get_count/#ishape) | 指定されたシェイプのエフェクト数を返します。 |


### 参照
* モジュール [`aspose.slides.animation`](/slides/python-net/ja/aspose.slides.animation)
* ライブラリ [`Aspose.Slides`](/slides/python-net)