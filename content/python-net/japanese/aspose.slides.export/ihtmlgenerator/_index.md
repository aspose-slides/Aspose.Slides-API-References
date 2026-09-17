---
title: IHtmlGenerator class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator クラス

HTML ジェネレータ。

IHtmlGenerator 型は次のメンバーを公開します:

## プロパティ

| Property | Description |
| :- | :- |
| [`slide_image_size`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/slide_image_size/) | スライド画像サイズを返します。<br/>            読み取り専用 **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | スライド画像サイズが指定される単位を返します。<br/>            読み取り専用 [`SvgCoordinateUnit`](/slides/python-net/ja/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | スライド画像サイズが指定される単位の CSS コードを返します。<br/>            読み取り専用 **str**. |
| [`previous_slide_index`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | 以前にレンダリングされたスライドのインデックス、または最初のスライドをレンダリング中の場合は -1 を返します。<br/>            読み取り専用 **int**. |
| [`slide_index`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/slide_index/) | 現在レンダリング中のスライドのインデックスを返します。<br/>            読み取り専用 **int**. |
| [`next_slide_index`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/next_slide_index/) | 現在のスライドの次にレンダリングされるスライドのインデックス、または現在最後のスライドをレンダリング中の場合は -1 を返します。<br/>            読み取り専用 **int**. |

## メソッド

| Method | Description |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/add_html/#str) | フォーマットされた HTML テキストを追加します。 |
| [`add_html(self, html)`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | フォーマットされた HTML テキストを追加します。 |
| [`add_html(self, html, start_index, length)`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | フォーマットされた HTML テキストを追加します。 |
| [`add_text(self, text)`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/add_text/#str) | HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。<br/>            改行と空白は置き換えられません。 |
| [`add_text(self, text)`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。<br/>            改行と空白は置き換えられません。 |
| [`add_text(self, text, start_index, length)`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。<br/>            改行と空白は置き換えられません。 |
| [`add_attribute_value(self, value)`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | 属性値をクオートし、HTML ファイルに追加します。 |
| [`add_attribute_value(self, value)`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | 属性値をクオートし、HTML ファイルに追加します。 |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/ja/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | 属性値をクオートし、HTML ファイルに追加します。 |

### 参照
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)