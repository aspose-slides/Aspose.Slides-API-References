---
title: TiffOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/tiffoptions/
---
## TiffOptions クラス

プレゼンテーションが TIFF 形式で保存される方法を制御するオプションを提供します。

**継承:**[`TiffOptions`](/slides/python-net/ja/aspose.slides.export/tiffoptions) → [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)

TiffOptions 型は次のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/tiffoptions/__init__/#) | デフォルトコンストラクタです。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/tiffoptions/warning_callback/) | 警告を受け取り、読み込みプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。<br/>            読み書き [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/tiffoptions/progress_callback/) | パーセンテージで保存進捗の更新を受け取るコールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/tiffoptions/default_regular_font/) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。<br/>            読み書き **str**. |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/tiffoptions/gradient_style/) | グラデーションの視覚スタイルを取得または設定します。<br/>            読み書き [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/tiffoptions/skip_java_script_links/) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 <br/>            読み書き **bool**. デフォルト値は **false** です。 |
| [`ink_options`](/slides/python-net/ja/aspose.slides.export/tiffoptions/ink_options/) | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。<br/>            読み取り専用 [`IInkOptions`](/slides/python-net/ja/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ja/aspose.slides.export/tiffoptions/show_hidden_slides/) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。<br/>            デフォルトは `false` です。 |
| [`image_size`](/slides/python-net/ja/aspose.slides.export/tiffoptions/image_size/) | 生成される TIFF 画像のサイズを指定します。<br/>            デフォルト値は 0x0 で、これは生成される画像サイズがプレゼンテーションのスライドサイズの値に基づいて計算されることを意味します。<br/>            読み書き [`Size`](/slides/python-net/ja/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/ja/aspose.slides.export/tiffoptions/dpi_x/) | 水平解像度（インチあたりのドット数）を指定します。<br/>            読み書き **int**. |
| [`dpi_y`](/slides/python-net/ja/aspose.slides.export/tiffoptions/dpi_y/) | 垂直解像度（インチあたりのドット数）を指定します。<br/>            読み書き **int**. |
| [`compression_type`](/slides/python-net/ja/aspose.slides.export/tiffoptions/compression_type/) | 圧縮タイプを指定します。<br/>            読み書き [`TiffCompressionTypes`](/slides/python-net/ja/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/ja/aspose.slides.export/tiffoptions/pixel_format/) | 生成される画像のピクセル形式を指定します。<br/>            読み書き [`ImagePixelFormat`](/slides/python-net/ja/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/ja/aspose.slides.export/tiffoptions/slides_layout_options/) | プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [`ISlidesLayoutOptions`](/slides/python-net/ja/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/ja/aspose.slides.export/tiffoptions/bw_conversion_mode/) | カラー画像を白黒画像に変換するアルゴリズムを指定します。<br/>            このオプションは [`TiffOptions.compression_type`](/slides/python-net/ja/aspose.slides.export/tiffoptions/compression_type) <br/>            が [`TiffCompressionTypes.CCITT4`](/slides/python-net/ja/aspose.slides.export/tiffcompressiontypes/CCITT4) または [`TiffCompressionTypes.CCITT3`](/slides/python-net/ja/aspose.slides.export/tiffcompressiontypes/CCITT3) に設定されている場合にのみ適用されます<br/>            読み書き [`BlackWhiteConversionMode`](/slides/python-net/ja/aspose.slides.export/blackwhiteconversionmode).<br/>            デフォルトは [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/ja/aspose.slides.export/blackwhiteconversionmode/DEFAULT). |

### 参照
* クラス [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)
* クラス [`TiffOptions`](/slides/python-net/ja/aspose.slides.export/tiffoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)