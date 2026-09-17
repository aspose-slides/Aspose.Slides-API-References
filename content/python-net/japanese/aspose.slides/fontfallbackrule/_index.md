---
title: FontFallBackRule class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/fontfallbackrule/
---
## FontFallBackRule クラス

フォント フォールバック ルールを表します

FontFallBackRule 型は次のメンバーを公開します:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/ja/aspose.slides/fontfallbackrule/__init__/#int-int-str) | 新しいインスタンスを作成します。 |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/ja/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | 新しいインスタンスを作成します。 |

## Properties

| Property | Description |
| :- | :- |
| [`range_start_index`](/slides/python-net/ja/aspose.slides/fontfallbackrule/range_start_index/) | 連続 Unicode 範囲の最初のインデックスを取得します。 |
| [`range_end_index`](/slides/python-net/ja/aspose.slides/fontfallbackrule/range_end_index/) | 連続 Unicode 範囲の最後のインデックスを取得します。 |
| [`count`](/slides/python-net/ja/aspose.slides/fontfallbackrule/count/) | 範囲に実際に定義されているフォント数を取得します。 読み取り専用 **int**。 |
|  | 指定されたインデックスのフォント名を取得します。 読み取り専用 [`IFontFallBackRule`](/slides/python-net/ja/aspose.slides/ifontfallbackrule)。 |

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/ja/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | 新しいフォントをFallBackフォントのリストに追加します。 |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/ja/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | 新しいフォントをFallBackフォントのリストに追加します。 |
| [`to_array(self)`](/slides/python-net/ja/aspose.slides/fontfallbackrule/to_array/#) | このルールのすべてのFallBackフォントを含む配列を作成して返します。 |
| [`to_array(self, start_index, count)`](/slides/python-net/ja/aspose.slides/fontfallbackrule/to_array/#int-int) | リスト内の指定された範囲のすべてのFallBackフォントを含む配列を作成して返します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides/fontfallbackrule/clear/#) | リストからすべてのフォントを削除します。 |
| [`remove(self, font_name)`](/slides/python-net/ja/aspose.slides/fontfallbackrule/remove/#str) | リストから特定のFallBackフォントの最初の出現を削除します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/fontfallbackrule/remove_at/#int) | リストの指定されたインデックスにあるFallBackフォントを削除します。 |
| [`index_of(self, font_name)`](/slides/python-net/ja/aspose.slides/fontfallbackrule/index_of/#str) | コレクション内の指定されたルールのインデックスを返します。 |

### 関連項目
* クラス [`IFontFallBackRule`](/slides/python-net/ja/aspose.slides/ifontfallbackrule)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)