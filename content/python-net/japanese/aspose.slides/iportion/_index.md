---
title: IPortion class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iportion/
---
## IPortion クラス

テキスト段落内のテキスト部分を表します。

IPortion 型は次のメンバーを公開します:

## プロパティ

| Property | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/ja/aspose.slides/iportion/portion_format/) | 明示的に設定された書式プロパティを含む、継承が適用されていないテキスト部分の書式オブジェクトを返します。<br/>            読み取り専用 [`IPortionFormat`](/slides/python-net/ja/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/ja/aspose.slides/iportion/text/) | 部分のプレーンテキストを取得または設定します。<br/>            読み書き可能 **str**. |
| [`field`](/slides/python-net/ja/aspose.slides/iportion/field/) | この部分のフィールドを返します。<br/>            読み取り専用 [`IField`](/slides/python-net/ja/aspose.slides/ifield). |
| [`slide`](/slides/python-net/ja/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/iportion/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/ja/aspose.slides/iportion/add_field/#ifieldtype) | この部分を自動更新フィールドに変換します。 |
| [`add_field(self, internal_string)`](/slides/python-net/ja/aspose.slides/iportion/add_field/#str) | この部分を自動更新フィールドに変換します。 |
| [`remove_field(self)`](/slides/python-net/ja/aspose.slides/iportion/remove_field/#) | このフィールド部分をシンプルな部分に変換します。 |
| [`get_rect(self)`](/slides/python-net/ja/aspose.slides/iportion/get_rect/#) | 部分を囲む矩形の座標を取得します。<br/>            矩形には、空の行も含め、部分内のすべてのテキスト行が含まれます。 |
| [`get_coordinates(self)`](/slides/python-net/ja/aspose.slides/iportion/get_coordinates/#) | 部分の開始位置の座標を取得します。ポイントの X 座標は、左サイドベアリングを含む最初の文字からの部分開始を表します。<br/>            Y 座標は上サイドベアリングを含みます。 |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)