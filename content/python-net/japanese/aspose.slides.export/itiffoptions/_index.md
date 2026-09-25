---
title: ITiffOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/itiffoptions/
---
## ITiffOptions クラス

プレゼンテーションをTIFF形式で保存する方法を制御するオプションを提供します。

ITiffOptions 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`image_size`](/slides/python-net/ja/aspose.slides.export/itiffoptions/image_size/) | 生成されたTIFF画像のサイズを指定します。<br/>            デフォルト値は0x0で、これは生成された画像サイズがプレゼンテーションのスライドサイズの値に基づいて計算されることを意味します。<br/>            読み取り/書き込み [`Size`](/slides/python-net/ja/aspose.slides/size). |
| [`dpi_x`](/slides/python-net/ja/aspose.slides.export/itiffoptions/dpi_x/) | 水平方向の解像度（インチあたりのドット数）を指定します。<br/>            読み取り/書き込み **int**. |
| [`dpi_y`](/slides/python-net/ja/aspose.slides.export/itiffoptions/dpi_y/) | 垂直方向の解像度（インチあたりのドット数）を指定します。<br/>            読み取り/書き込み **int**. |
| [`show_hidden_slides`](/slides/python-net/ja/aspose.slides.export/itiffoptions/show_hidden_slides/) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。<br/>            デフォルトは `false` です。 |
| [`compression_type`](/slides/python-net/ja/aspose.slides.export/itiffoptions/compression_type/) | 圧縮タイプを指定します。<br/>            読み取り/書き込み [`TiffCompressionTypes`](/slides/python-net/ja/aspose.slides.export/tiffcompressiontypes). |
| [`pixel_format`](/slides/python-net/ja/aspose.slides.export/itiffoptions/pixel_format/) | 生成された画像のピクセル形式を指定します。<br/>            読み取り/書き込み [`ImagePixelFormat`](/slides/python-net/ja/aspose.slides.export/imagepixelformat). |
| [`slides_layout_options`](/slides/python-net/ja/aspose.slides.export/itiffoptions/slides_layout_options/) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [`ISlidesLayoutOptions`](/slides/python-net/ja/aspose.slides.export/islideslayoutoptions). |
| [`bw_conversion_mode`](/slides/python-net/ja/aspose.slides.export/itiffoptions/bw_conversion_mode/) | カラー画像を白黒画像に変換するアルゴリズムを指定します。<br/>            このオプションは [`ITiffOptions.compression_type`](/slides/python-net/ja/aspose.slides.export/itiffoptions/compression_type) <br/>            が [`TiffCompressionTypes.CCITT4`](/slides/python-net/ja/aspose.slides.export/tiffcompressiontypes/CCITT4) または [`TiffCompressionTypes.CCITT3`](/slides/python-net/ja/aspose.slides.export/tiffcompressiontypes/CCITT3) に設定されている場合にのみ適用されます。<br/>            読み取り/書き込み [`BlackWhiteConversionMode`](/slides/python-net/ja/aspose.slides.export/blackwhiteconversionmode)。<br/>            デフォルトは [`BlackWhiteConversionMode.DEFAULT`](/slides/python-net/ja/aspose.slides.export/blackwhiteconversionmode/DEFAULT)です。 |
| [`ink_options`](/slides/python-net/ja/aspose.slides.export/itiffoptions/ink_options/) | エクスポートされたドキュメント内のインクオブジェクトの外観を制御するオプションを提供します。<br/>            読み取り専用 [`IInkOptions`](/slides/python-net/ja/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/itiffoptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/itiffoptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/itiffoptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/itiffoptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/itiffoptions/skip_java_script_links/) |  |

### 参照
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)