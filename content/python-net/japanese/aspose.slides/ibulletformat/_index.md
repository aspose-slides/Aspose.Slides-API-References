---
title: IBulletFormat class
second_title: Aspose.Slides の Python 用 .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ibulletformat/
---
## IBulletFormat クラス

段落の箇条書き書式設定プロパティを表します。

IBulletFormat 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`type`](/slides/python-net/ja/aspose.slides/ibulletformat/type/) | 継承なしの段落の箇条書きタイプを取得または設定します。<br/> 読み書き [`BulletType`](/slides/python-net/ja/aspose.slides/bullettype)。 |
| [`char`](/slides/python-net/ja/aspose.slides/ibulletformat/char/) | 継承なしの段落の箇条書き文字を取得または設定します。<br/> 読み書き **System.Char**。 |
| [`font`](/slides/python-net/ja/aspose.slides/ibulletformat/font/) | 継承なしの段落の箇条書きフォントを取得または設定します。<br/> 読み書き [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata)。 |
| [`height`](/slides/python-net/ja/aspose.slides/ibulletformat/height/) | 継承なしの段落の箇条書き高さを取得または設定します。<br/> float.NaN の値は、箇条書きが段落の最初の部分から高さを継承することを示します。<br/> 読み書き **float**。 |
| [`color`](/slides/python-net/ja/aspose.slides/ibulletformat/color/) | 継承なしの段落の箇条書きのカラー形式を取得します。<br/> 読み取り専用 [`IColorFormat`](/slides/python-net/ja/aspose.slides/icolorformat)。 |
| [`picture`](/slides/python-net/ja/aspose.slides/ibulletformat/picture/) | 継承なしの段落で箇条書きとして使用される画像を取得します。<br/> 読み取り専用 [`ISlidesPicture`](/slides/python-net/ja/aspose.slides/islidespicture)。 |
| [`numbered_bullet_start_with`](/slides/python-net/ja/aspose.slides/ibulletformat/numbered_bullet_start_with/) | 継承なしの番号付き箇条書きグループで使用される最初の番号を取得または設定します。<br/> 読み書き **int**。 |
| [`numbered_bullet_style`](/slides/python-net/ja/aspose.slides/ibulletformat/numbered_bullet_style/) | 継承なしの番号付き箇条書きのスタイルを取得または設定します。<br/> 読み書き [`IBulletFormat.numbered_bullet_style`](/slides/python-net/ja/aspose.slides/ibulletformat/numbered_bullet_style)。 |
| [`is_bullet_hard_color`](/slides/python-net/ja/aspose.slides/ibulletformat/is_bullet_hard_color/) | 箇条書きが独自の色を持つか、段落の最初の部分から色を継承するかを決定します。<br/> **NullableBool.True** は箇条書きが独自の色を持つ場合、**NullableBool.False** は段落の最初の部分から色を継承する場合です。<br/> 読み書き [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool)。 |
| [`is_bullet_hard_font`](/slides/python-net/ja/aspose.slides/ibulletformat/is_bullet_hard_font/) | 箇条書きが独自のフォントを持つか、段落の最初の部分からフォントを継承するかを決定します。<br/> **NullableBool.True** は箇条書きが独自のフォントを持つ場合、**NullableBool.False** は段落の最初の部分からフォントを継承する場合です。<br/> 読み書き [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool)。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/ja/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/#) | 箇条書きが有効な場合（PowerPoint が段落の箇条書き/番号付けを有効にしたときと同様）、有効な段落の Indent と MarginLeft に対してデフォルトの非ゼロシフトを設定します。箇条書きが無効な場合は、段落の Indent と MarginLeft をリセットします（PowerPoint が段落の箇条書き/番号付けを無効にしたときと同様）。インデントシフトは現在の箇条書きコンテキスト（IBulletFormat.Type、.NumberedBulletStyle、最初の部分の FontHeight）に基づいて適用されます。非ゼロのインデントシフトは現在の段落の有効な Indent と MarginLeft に適用され、結果の値はローカルな値になります。 |
| [`get_effective(self)`](/slides/python-net/ja/aspose.slides/ibulletformat/get_effective/#) | 継承が適用された有効な箇条書き書式設定データを取得します。 |

### 関連項目
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)