---
title: ISmartArtNode class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.smartart/ismartartnode/
---
## ISmartArtNode クラス

SmartArt ダイアグラムのノードを表します。

ISmartArtNode 型は以下のメンバーを公開します：

## プロパティ

| Property | Description |
| :- | :- |
| [`child_nodes`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode/child_nodes/) | 現在のノードのすべての子ノードのコレクションを返します。<br/>            読み取り専用 [`ISmartArtNodeCollection`](/slides/python-net/ja/aspose.slides.smartart/ismartartnodecollection)。 |
| [`shapes`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode/shapes/) | ノードに関連付けられたすべてのシェイプのコレクションを返します。<br/>            読み取り専用 [`ISmartArtShapeCollection`](/slides/python-net/ja/aspose.slides.smartart/ismartartshapecollection)。 |
| [`text_frame`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode/text_frame/) | ノードのテキストを取得または設定します。<br/>            読み取り専用 [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe)。 |
| [`is_assistant`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode/is_assistant/) | ノードをアシスタントとして取得または設定します。<br/>            読み取り/書き込み **bool**。 |
| [`level`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode/level/) | ノードのネストレベルを返します。<br/>            読み取り専用 **int**。 |
| [`bullet_fill_format`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode/bullet_fill_format/) | ノードの箇条書きの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。<br/>            注: ノードに箇条書きが提供されない特定の SmartArt レイアウトの場合、None を返すことがあります。<br/>            読み取り専用 [`IFillFormat`](/slides/python-net/ja/aspose.slides/ifillformat)。 |
| [`position`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode/position/) | ノードの兄弟ノード間でのゼロベース位置を取得または設定します。<br/>            読み取り/書き込み **int**。 |
| [`is_hidden`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode/is_hidden/) | このノードがデータモデルで非表示ノードである場合は true を返します。<br/>            読み取り専用 **bool**。 |
| [`organization_chart_layout`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode/organization_chart_layout/) | 現在のノードに関連付けられた組織図レイアウトタイプを取得または設定します。<br/>            読み取り/書き込み [`OrganizationChartLayoutType`](/slides/python-net/ja/aspose.slides.smartart/organizationchartlayouttype)。 |

## メソッド

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides.smartart/ismartartnode/remove/#) | 現在のノードを削除します。 |

### 参照
* モジュール [`aspose.slides.smartart`](/slides/python-net/ja/aspose.slides.smartart)
* ライブラリ [`Aspose.Slides`](/slides/python-net)