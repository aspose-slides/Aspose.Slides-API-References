---
title: IParagraph class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iparagraph/
---
## IParagraph クラス

テキストの段落を表します。

IParagraph 型は以下のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`portions`](/slides/python-net/ja/aspose.slides/iparagraph/portions/) | テキスト部分のコレクションを返します。<br/>            読み取り専用 [`IPortionCollection`](/slides/python-net/ja/aspose.slides/iportioncollection). |
| [`paragraph_format`](/slides/python-net/ja/aspose.slides/iparagraph/paragraph_format/) | この段落の書式設定オブジェクトを返します。<br/>            読み取り専用 [`IParagraphFormat`](/slides/python-net/ja/aspose.slides/iparagraphformat). |
| [`text`](/slides/python-net/ja/aspose.slides/iparagraph/text/) | 段落のプレーンテキストを取得または設定します。<br/>            読み取り/書き込み **str**. |
| [`end_paragraph_portion_format`](/slides/python-net/ja/aspose.slides/iparagraph/end_paragraph_portion_format/) | 最後の部分の後に別の部分が挿入された場合に使用される部分プロパティを指定します。<br/>            |
| [`slide`](/slides/python-net/ja/aspose.slides/iparagraph/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/iparagraph/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`get_image(self)`](/slides/python-net/ja/aspose.slides/iparagraph/get_image/#) | 段落の画像を返します。 |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/ja/aspose.slides/iparagraph/get_image/#float-float) | 指定されたスケールで段落の画像を返します。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/ja/aspose.slides/iparagraph/join_portions_with_same_formatting/#) | 同じ書式設定のランを結合します。 |
| [`get_rect(self)`](/slides/python-net/ja/aspose.slides/iparagraph/get_rect/#) | 段落を囲む矩形の座標を取得します。<br/>            矩形には段落内のすべてのテキスト行が含まれ、空行も含まれます。 |
| [`get_lines_count(self)`](/slides/python-net/ja/aspose.slides/iparagraph/get_lines_count/#) | 段落の行数を取得します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)