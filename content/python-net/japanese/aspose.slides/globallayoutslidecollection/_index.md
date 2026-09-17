---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection クラス

プレゼンテーション内のすべてのレイアウト スライドのコレクションを表します。  
LayoutSlideCollection クラスを拡張し、個々のマスター レイアウト スライド コレクションを統合するコンテキストで、レイアウト スライドの追加/クローン作成用のメソッドを提供します。

**継承:**[`GlobalLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/ja/aspose.slides/layoutslidecollection)

GlobalLayoutSlideCollection 型は次のメンバーを公開します。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/ja/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | 指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。 |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/ja/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | 指定されたレイアウト スライドのコピーをプレゼンテーションに追加します。 |
| [`get_by_type(self, type)`](/slides/python-net/ja/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | 指定されたタイプの最初のレイアウト スライドを返します。<br/>            見つけるレイアウト スライドのタイプ。[`LayoutSlide`](/slides/python-net/ja/aspose.slides/layoutslide) で指定されたタイプのもの、またはレイアウトが見つからない場合は None を返します。 |
| [`remove(self, value)`](/slides/python-net/ja/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | コレクションからレイアウトを削除します。 |
| [`remove_unused(self)`](/slides/python-net/ja/aspose.slides/globallayoutslidecollection/remove_unused/#) | 未使用のレイアウト スライドを削除します (HasDependingSlides が false のレイアウト スライド)。 |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/ja/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | 新しいレイアウト スライドをプレゼンテーションに追加します。 |

### 参照
* クラス [`GlobalLayoutSlideCollection`](/slides/python-net/ja/aspose.slides/globallayoutslidecollection)
* クラス [`LayoutSlideCollection`](/slides/python-net/ja/aspose.slides/layoutslidecollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)