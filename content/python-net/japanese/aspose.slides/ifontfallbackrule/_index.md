---
title: IFontFallBackRule class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ifontfallbackrule/
---
## IFontFallBackRule クラス

フォントフォールバックルールを表します。

IFontFallBackRule 型は以下のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`range_start_index`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/range_start_index/) | 連続 Unicode 範囲の最初のインデックスを取得します。 |
| [`range_end_index`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/range_end_index/) | 連続 Unicode 範囲の最後のインデックスを取得します。 |
| [`count`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/count/) | 範囲に実際に定義されているフォント数を取得します。 |

指定したインデックスのフォント名を取得します。

## インデクサー

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/__getitem__/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#str) | FallBack フォントのリストに新しいフォントを追加します。 |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#liststr) | FallBack フォントのリストに新しいフォントを追加します。 |
| [`to_array(self)`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/to_array/#) | このルールのすべての FallBack フォントを含む配列を作成して返します。 |
| [`to_array(self, start_index, count)`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/to_array/#int-int) | リスト内の指定された範囲のすべての FallBack フォントを含む配列を作成して返します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/clear/#) | リストからすべてのフォントを削除します。 |
| [`remove(self, font_name)`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/remove/#str) | リストから特定の FallBack フォントの最初の出現を削除します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/remove_at/#int) | リストの指定インデックスにある FallBack フォントを削除します。 |
| [`index_of(self, font_name)`](/slides/python-net/ja/aspose.slides/ifontfallbackrule/index_of/#str) | コレクション内の指定されたルールのインデックスを返します。 |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)