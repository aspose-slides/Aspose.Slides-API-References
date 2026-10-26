---
title: Paragraph class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/paragraph/
---
## Paragraph クラス

テキストの段落を表します。

Paragraph 型は次のメンバーを公開します:

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides/paragraph/__init__/#) | Paragraph クラスの新しいインスタンスをデフォルトプロパティで初期化します。 |
| [`__init__(self, para)`](/slides/python-net/ja/aspose.slides/paragraph/__init__/#paragraph) | Paragraph クラスの新しいインスタンスを初期化するコピーコンストラクタです。 |

## プロパティ

| Property | Description |
| :- | :- |
| [`portions`](/slides/python-net/ja/aspose.slides/paragraph/portions/) | テキスト部分のコレクションを返します。<br/>            読み取り専用 [`IPortionCollection`](/slides/python-net/ja/aspose.slides/iportioncollection). |
| [`paragraph_format`](/slides/python-net/ja/aspose.slides/paragraph/paragraph_format/) | この段落の書式設定オブジェクトを返します。<br/>            読み取り専用 [`IParagraphFormat`](/slides/python-net/ja/aspose.slides/iparagraphformat). |
| [`text`](/slides/python-net/ja/aspose.slides/paragraph/text/) | 段落のプレーンテキストを取得または設定します。<br/>            読み取り/書き込み **str**. |
| [`end_paragraph_portion_format`](/slides/python-net/ja/aspose.slides/paragraph/end_paragraph_portion_format/) | 別の部分が挿入される場合に使用される部分プロパティを指定します<br/>            最後のものの後。 |
| [`slide`](/slides/python-net/ja/aspose.slides/paragraph/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/paragraph/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/paragraph/get_image/#) | 段落の画像を返します。 |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/paragraph/get_image/#float-float) | 指定されたスケールで段落の画像を返します。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/paragraph/join_portions_with_same_formatting/#) | 同じ書式のランを結合します。 |
| [`get_rect(self)`](/slides/python-net/ja/aspose.slides/paragraph/get_rect/#) | 段落を囲む矩形の座標を取得します。矩形には段落内のすべてのテキスト行が含まれます<br/>            空行も含む。 |
| [`get_lines_count(self)`](/slides/python-net/ja/aspose.slides/paragraph/get_lines_count/#) | 段落の行数を取得します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)