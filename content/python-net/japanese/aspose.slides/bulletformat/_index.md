---
title: BulletFormat class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/bulletformat/
---
## BulletFormat クラス

段落の箇条書き書式設定プロパティを表します。

**継承:**[`BulletFormat`](/slides/python-net/ja/aspose.slides/bulletformat) → [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)

BulletFormat 型は次のメンバーを公開します:

## プロパティ

| Property | Description |
| :- | :- |
| [`type`](/slides/python-net/ja/aspose.slides/bulletformat/type/) | 段落に継承がない場合の箇条書きタイプを取得または設定します。<br/>            読み取り/書き込み [`BulletType`](/slides/python-net/ja/aspose.slides/bullettype). |
| [`char`](/slides/python-net/ja/aspose.slides/bulletformat/char/) | 段落に継承がない場合の箇条書き文字を取得または設定します。<br/>            読み取り/書き込み **System.Char**. |
| [`font`](/slides/python-net/ja/aspose.slides/bulletformat/font/) | 段落に継承がない場合の箇条書きフォントを取得または設定します。<br/>            読み取り/書き込み [`IFontData`](/slides/python-net/ja/aspose.slides/ifontdata). |
| [`height`](/slides/python-net/ja/aspose.slides/bulletformat/height/) | 段落に継承がない場合の箇条書き高さを取得または設定します。<br/>            値 float.NaN は、箇条書きが段落の最初の部分から高さを継承することを示します。<br/>            読み取り/書き込み **float**. |
| [`color`](/slides/python-net/ja/aspose.slides/bulletformat/color/) | 段落に継承がない場合の箇条書きの色形式を取得します。<br/>            読み取り専用 [`IColorFormat`](/slides/python-net/ja/aspose.slides/icolorformat). |
| [`numbered_bullet_start_with`](/slides/python-net/ja/aspose.slides/bulletformat/numbered_bullet_start_with/) | 段落に継承がない場合の番号付き箇条書きグループに使用される最初の番号を取得または設定します。<br/>            読み取り/書き込み **int**. |
| [`numbered_bullet_style`](/slides/python-net/ja/aspose.slides/bulletformat/numbered_bullet_style/) | 段落に継承がない場合の番号付き箇条書きのスタイルを取得または設定します。<br/>            読み取り/書き込み [`NumberedBulletStyle`](/slides/python-net/ja/aspose.slides/numberedbulletstyle). |
| [`is_bullet_hard_color`](/slides/python-net/ja/aspose.slides/bulletformat/is_bullet_hard_color/) | 段落に継承がない場合の箇条書きが独自の色を持つか、段落の最初の部分から継承するかを決定します。<br/>            **NullableBool.True**  は箇条書きが独自の色を持つ場合、**NullableBool.False**  は段落の最初の部分から色を継承する場合です。<br/>            読み取り/書き込み [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`is_bullet_hard_font`](/slides/python-net/ja/aspose.slides/bulletformat/is_bullet_hard_font/) | 段落に継承がない場合の箇条書きが独自のフォントを持つか、段落の最初の部分から継承するかを決定します。<br/>            **NullableBool.True**  は箇条書きが独自のフォントを持つ場合、**NullableBool.False**  は段落の最初の部分からフォントを継承する場合です。<br/>            読み取り/書き込み [`NullableBool`](/slides/python-net/ja/aspose.slides/nullablebool). |
| [`picture`](/slides/python-net/ja/aspose.slides/bulletformat/picture/) | 段落に継承がない場合の箇条書きとして使用される画像を取得します。<br/>            読み取り専用 [`ISlidesPicture`](/slides/python-net/ja/aspose.slides/islidespicture). |
| [`slide`](/slides/python-net/ja/aspose.slides/bulletformat/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides/bulletformat/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`apply_default_paragraph_indents_shifts(self)`](/slides/python-net/ja/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/#) | 箇条書きが有効な場合（PowerPoint が段落の箇条書き/番号付けを有効にしたときと同様）、有効な段落の Indent と MarginLeft に対してデフォルトの非ゼロシフトを設定します。箇条書きが無効な場合は、段落の Indent と MarginLeft をリセットします（PowerPoint が段落の箇条書き/番号付けを無効にしたときと同様）。インデントシフトは現在の箇条書きコンテキスト（IBulletFormat.Type、.NumberedBulletStyle、および最初の部分の FontHeight）に基づいて適用されます。非ゼロのインデントシフトは現在の段落の有効な Indent と MarginLeft に適用され（結果の値をローカル値にします）。 |
| [`get_effective(self)`](/slides/python-net/ja/aspose.slides/bulletformat/get_effective/#) | 継承が適用された有効な箇条書き書式設定データを取得します。 |

### 参照
* クラス [`BulletFormat`](/slides/python-net/ja/aspose.slides/bulletformat)
* クラス [`PVIObject`](/slides/python-net/ja/aspose.slides/pviobject)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)