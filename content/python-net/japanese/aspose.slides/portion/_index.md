---
title: Portion class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/portion/
---
## Portion クラス

テキスト段落内のテキストの一部を表します。

Portion 型は次のメンバーを公開します。

## コンストラクタ

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides/portion/__init__/#) | Portion クラスの新しいインスタンスを初期化します。 |
| [`__init__(self, str)`](/slides/python-net/ja/aspose.slides/portion/__init__/#str) | Portion クラスの新しいインスタンスを初期化します。 |
| [`__init__(self, portion)`](/slides/python-net/ja/aspose.slides/portion/__init__/#portion) | Portion クラスの新しいインスタンスを初期化します。 |

## プロパティ

| Property | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/ja/aspose.slides/portion/portion_format/) | 継承が適用されていないテキスト部分の明示的に設定された書式プロパティを含む書式オブジェクトを返します。<br/>            読み取り専用 [`IPortionFormat`](/slides/python-net/ja/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/ja/aspose.slides/portion/text/) | 部分のプレーンテキストを取得または設定します。<br/>            読み書き **str**. |
| [`field`](/slides/python-net/ja/aspose.slides/portion/field/) | この部分のフィールドを返します。<br/>            読み取り専用 [`IField`](/slides/python-net/ja/aspose.slides/ifield). |
| [`slide`](/slides/python-net/ja/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/portion/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/ja/aspose.slides/portion/add_field/#ifieldtype) | この部分を自動的に更新されるフィールドに変換します。 |
| [`add_field(self, internal_string)`](/slides/python-net/ja/aspose.slides/portion/add_field/#str) | この部分を自動的に更新されるフィールドに変換します。 |
| [`remove_field(self)`](/slides/python-net/ja/aspose.slides/portion/remove_field/#) | このフィールド部分をシンプルな部分に変換します。 |
| [`get_rect(self)`](/slides/python-net/ja/aspose.slides/portion/get_rect/#) | 部分を囲む矩形の座標を取得します。矩形には、空の行を含む部分内の<br/>テキストのすべての行が含まれます。 |
| [`get_coordinates(self)`](/slides/python-net/ja/aspose.slides/portion/get_coordinates/#) | 部分の開始位置の座標を取得します。ポイントのX座標は、左側ベアリングを含む最初の文字からの部分の開始位置を表します。<br/>Y座標は上側ベアリングを含みます。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)