---
title: MathPortion class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathportion/
---
## MathPortion クラス

数式コンテキストを持つ部分を表します。

**Inheritance:**[`MathPortion`](/slides/python-net/ja/aspose.slides.mathtext/mathportion) → [`Portion`](/slides/python-net/ja/aspose.slides/portion)

MathPortion 型は次のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/__init__/#) | MathPortion クラスの新しいインスタンスを初期化します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`portion_format`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/portion_format/) | 継承が適用されていないテキスト部分の明示的に設定された書式プロパティを含むフォーマットオブジェクトを返します。<br/>            読み取り専用 [`IPortionFormat`](/slides/python-net/ja/aspose.slides/iportionformat)。 |
| [`text`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/text/) | 部分のプレーンテキストを取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`field`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/field/) | この部分のフィールドを返します。<br/>            読み取り専用 [`IField`](/slides/python-net/ja/aspose.slides/ifield)。 |
| [`math_paragraph`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/math_paragraph/) | 数式段落 |
| [`slide`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/presentation/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/add_field/#ifieldtype) | この部分を自動的に更新されるフィールドに変換します。 |
| [`add_field(self, internal_string)`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/add_field/#str) | この部分を自動的に更新されるフィールドに変換します。 |
| [`remove_field(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/remove_field/#) | このフィールド部分を単純な部分に変換します。 |
| [`get_rect(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/get_rect/#) | 部分を囲む矩形の座標を取得します。矩形は部分内のすべてのテキスト行（空行も含む）を含みます。 |
| [`get_coordinates(self)`](/slides/python-net/ja/aspose.slides.mathtext/mathportion/get_coordinates/#) | 部分の開始位置の座標を取得します。点の X 座標は左サイドベアリングを含む最初の文字からの部分の開始を表します。Y 座標はトップサイドベアリングを含みます。 |


### 参照
* クラス [`MathPortion`](/slides/python-net/ja/aspose.slides.mathtext/mathportion)
* クラス [`Portion`](/slides/python-net/ja/aspose.slides/portion)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)