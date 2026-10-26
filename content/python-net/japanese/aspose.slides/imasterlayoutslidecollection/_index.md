---
title: IMasterLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET の API リファレンス
description: 
type: docs
url: /ja/aspose.slides/imasterlayoutslidecollection/
---
## IMasterLayoutSlideCollection クラス

定義されたマスタースライドのすべてのレイアウトスライドのコレクションを表します。
ILayoutSlideCollection インターフェイスを拡張し、マスターのレイアウトスライドの個々のコレクションのコンテキストでレイアウトスライドを追加/挿入/削除/クローンするためのメソッドを提供します。

IMasterLayoutSlideCollection 型は次のメンバーを公開します:

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection/add_clone/#ilayoutslide) | 指定されたレイアウトスライドのコピーをコレクションの末尾に追加します。 |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection/insert_clone/#int-ilayoutslide) | 指定されたレイアウトスライドのコピーをコレクションの指定位置に挿入します。 |
| [`add(self, layout_type, layout_name)`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection/add/#slidelayouttype-str) | 新しいレイアウトスライドをコレクションの末尾に追加します。 |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection/insert/#int-slidelayouttype-str) | 新しいレイアウトスライドをコレクションの指定位置に挿入します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection/remove_at/#int) | コレクションの指定インデックスにある要素を削除します。 |
| [`reorder(self, index, layout_slide)`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection/reorder/#int-ilayoutslide) | レイアウトスライドをコレクションから指定位置へ移動します。 |
| [`get_by_type(self, type)`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection/get_by_type/#slidelayouttype) |  |
| [`remove(self, value)`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection/remove/#ilayoutslide) |  |
| [`remove_unused(self)`](/slides/python-net/ja/aspose.slides/imasterlayoutslidecollection/remove_unused/#) |  |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)