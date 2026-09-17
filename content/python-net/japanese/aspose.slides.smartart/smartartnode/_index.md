---
title: SmartArtNode class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.smartart/smartartnode/
---
## SmartArtNode クラス

SmartArt オブジェクトのノードを表します

SmartArtNode 型は以下のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`child_nodes`](/slides/python-net/ja/aspose.slides.smartart/smartartnode/child_nodes/) | 現在のノードのすべての子ノードのコレクションを返します。<br/>            読み取り専用 [`ISmartArtNodeCollection`](/slides/python-net/ja/aspose.slides.smartart/ismartartnodecollection)。 |
| [`shapes`](/slides/python-net/ja/aspose.slides.smartart/smartartnode/shapes/) | ノードに関連付けられたすべての形状のコレクションを返します。<br/>            読み取り専用 [`ISmartArtShapeCollection`](/slides/python-net/ja/aspose.slides.smartart/ismartartshapecollection)。 |
| [`text_frame`](/slides/python-net/ja/aspose.slides.smartart/smartartnode/text_frame/) | ノードのテキスト フレームを返します。<br/>            読み取り専用 [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe)。 |
| [`is_assistant`](/slides/python-net/ja/aspose.slides.smartart/smartartnode/is_assistant/) | ノードをアシスタントとして取得または設定します。<br/>            読み書き **bool**。 |
| [`level`](/slides/python-net/ja/aspose.slides.smartart/smartartnode/level/) | ノードのネスト レベルを返します。<br/>            読み取り専用 **int**。 |
| [`bullet_fill_format`](/slides/python-net/ja/aspose.slides.smartart/smartartnode/bullet_fill_format/) | ノードの箇条書きの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: ノードに箇条書きが提供されない特定の SmartArt レイアウトの場合、None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`position`](/slides/python-net/ja/aspose.slides.smartart/smartartnode/position/) | 兄弟ノード間におけるノードの 0 ベース位置を取得または設定します。<br/>            読み書き **int**。 |
| [`is_hidden`](/slides/python-net/ja/aspose.slides.smartart/smartartnode/is_hidden/) | このノードがデータモデル内の非表示ノードである場合に true を返します。<br/>            読み取り専用 **bool**。 |
| [`organization_chart_layout`](/slides/python-net/ja/aspose.slides.smartart/smartartnode/organization_chart_layout/) | 現在のノードに関連付けられた組織図レイアウト タイプを取得または設定します。<br/>            読み書き [`OrganizationChartLayoutType`](/slides/python-net/ja/aspose.slides.smartart/organizationchartlayouttype)。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides.smartart/smartartnode/remove/#) | 現在のノードを削除します。 |

### 参照
* モジュール [`aspose.slides.smartart`](/slides/python-net/ja/aspose.slides.smartart)
* ライブラリ [`Aspose.Slides`](/slides/python-net)