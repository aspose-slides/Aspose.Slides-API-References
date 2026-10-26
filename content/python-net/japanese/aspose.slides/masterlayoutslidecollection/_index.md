---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection クラス

定義されたマスタースライドのすべてのレイアウトスライドのコレクションを表します。  
LayoutSlideCollection クラスを拡張し、マスターのレイアウトスライドの個々のコレクションのコンテキストでレイアウトスライドを追加/挿入/削除/クローン作成/順序変更するメソッドを提供します。

**継承:**[`MasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/ja/aspose.slides/layoutslidecollection)

MasterLayoutSlideCollection 型は以下のメンバーを公開します:

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | 指定されたタイプの最初のレイアウトスライドを返します。<br/>            探すレイアウトスライドのタイプです。[`LayoutSlide`](/slides/python-net/ja/aspose.slides/layoutslide) が指定されたタイプのレイアウトが見つからない場合は None を返します。 |
| [`remove(self, value)`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | コレクションからレイアウトを削除します。 |
| [`remove_unused(self)`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection/remove_unused/#) | 未使用のレイアウトスライドを削除します（HasDependingSlides が false のレイアウトスライド）。 |
| [`add_clone(self, source_layout)`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | 指定されたレイアウトスライドのコピーをコレクションの末尾に追加します。 |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | 指定されたレイアウトスライドのコピーをコレクションの指定位置に挿入します。 |
| [`add(self, layout_type, layout_name)`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | 新しいレイアウトスライドをコレクションの末尾に追加します。 |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | 新しいレイアウトスライドをコレクションの指定位置に挿入します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection/remove_at/#int) | コレクションの指定インデックスにある要素を削除します。 |
| [`reorder(self, index, layout_slide)`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | レイアウトスライドをコレクション内で指定された位置に移動します。 |

### 参照
* クラス [`LayoutSlideCollection`](/slides/python-net/ja/aspose.slides/layoutslidecollection)
* クラス [`MasterLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/masterlayoutslidecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)