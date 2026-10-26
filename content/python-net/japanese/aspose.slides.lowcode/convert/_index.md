---
title: Convert class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.lowcode/convert/
---
## Convert クラス

[`Presentation`](/slides/python-net/ja/aspose.slides/presentation) を変換することを目的としたメソッドのグループを表します。

Convert 型は以下のメンバーを公開します。

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`to_pdf(pres_path, out_path)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_pdf/#str-str) | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) を PDF に変換します。 |
| [`to_pdf(pres_path, out_path, options)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_pdf/#str-str-asposeslidesexportipdfoptions) | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) を PDF に変換します。 |
| [`to_pdf(pres, out_path)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_pdf/#presentation-str) | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) を PDF に変換します。 |
| [`to_pdf(pres, out_path, options)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_pdf/#presentation-str-asposeslidesexportipdfoptions) | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) を PDF に変換します。 |
| [`to_svg(pres_path)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_svg/#str) | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) を SVG に変換します。 |
| [`to_svg(pres, options)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_svg/#presentation-asposeslidesexportisvgoptions) | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) を SVG に変換します。 |
| [`to_jpeg(pres, output_file_name)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_jpeg/#presentation-str) | 入力プレゼンテーションを JPEG 形式の画像セットに変換します。  <br/>            出力ファイル名が "myPath/myFilename.jpeg" の場合、 <br/>            結果は "myPath/myFilename_N.jpeg" ファイルのセットとして保存されます。N はスライド番号です。 |
| [`to_jpeg(pres, output_file_name, image_size)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_jpeg/#presentation-str-asposeslidessize) | 入力プレゼンテーションを JPEG 形式の画像セットに変換します。  <br/>            出力ファイル名が "myPath/myFilename.jpeg" の場合、 <br/>            結果は "myPath/myFilename_N.jpeg" ファイルのセットとして保存されます。N はスライド番号です。 |
| [`to_jpeg(pres, output_file_name, scale, options)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_jpeg/#presentation-str-float-asposeslidesexportirenderingoptions) | 入力プレゼンテーションを JPEG 形式の画像セットに変換します。  <br/>            出力ファイル名が "myPath/myFilename.jpeg" の場合、 <br/>            結果は "myPath/myFilename_N.jpeg" ファイルのセットとして保存されます。N はスライド番号です。 |
| [`to_png(pres, output_file_name)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_png/#presentation-str) | 入力プレゼンテーションを PNG 形式の画像セットに変換します。  <br/>            出力ファイル名が "myPath/myFilename.png" の場合、 <br/>            結果は "myPath/myFilename_N.png" ファイルのセットとして保存されます。N はスライド番号です。 |
| [`to_png(pres, output_file_name, image_size)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_png/#presentation-str-asposeslidessize) | 入力プレゼンテーションを PNG 形式の画像セットに変換します。  <br/>            出力ファイル名が "myPath/myFilename.png" の場合、 <br/>            結果は "myPath/myFilename_N.png" ファイルのセットとして保存されます。N はスライド番号です。 |
| [`to_png(pres, output_file_name, scale, options)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_png/#presentation-str-float-asposeslidesexportirenderingoptions) | 入力プレゼンテーションを PNG 形式の画像セットに変換します。  <br/>            出力ファイル名が "myPath/myFilename.png" の場合、 <br/>            結果は "myPath/myFilename_N.png" ファイルのセットとして保存されます。N はスライド番号です。 |
| [`to_tiff(pres, output_file_name)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_tiff/#presentation-str) | 入力プレゼンテーションを TIFF 形式の画像セットに変換します。  <br/>            出力ファイル名が "myPath/myFilename.tiff" の場合、 <br/>            結果は "myPath/myFilename_N.tiff" ファイルのセットとして保存されます。N はスライド番号です。 |
| [`to_tiff(pres, output_file_name, options, multipage)`](/slides/python-net/ja/aspose.slides.lowcode/convert/to_tiff/#presentation-str-asposeslidesexportitiffoptions-bool) | カスタムオプションで入力プレゼンテーションを TIFF 形式に変換します。<br/>            出力ファイル名が "myPath/myFilename.tiff" で `multipage` が `false` の場合、 <br/>            結果は "myPath/myFilename_N.tiff" ファイルのセットとして保存されます。N はスライド番号です。<br/>            それ以外で `multipage` が `true` の場合、結果はマルチページの "myPath/myFilename.tiff" ドキュメントになります。 |
| [`auto_by_extension(pres_path, out_path)`](/slides/python-net/ja/aspose.slides.lowcode/convert/auto_by_extension/#str-str) | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) を渡された出力パス拡張子を使用して変換し、必要なエクスポート形式を決定します。 |

### 参照
* クラス [`Presentation`](/slides/python-net/ja/aspose.slides/presentation)
* モジュール [`aspose.slides.lowcode`](/slides/python-net/ja/aspose.slides.lowcode)
* ライブラリ [`Aspose.Slides`](/slides/python-net)