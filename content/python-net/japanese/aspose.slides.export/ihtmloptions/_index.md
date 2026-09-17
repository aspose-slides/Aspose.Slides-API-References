---
title: IHtmlOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/ihtmloptions/
---
## IHtmlOptions クラス

HTML エクスポート オプションを表します。

IHtmlOptions 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`html_formatter`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/html_formatter/) | HTMLテンプレートを取得または設定します。<br/>            読み取り/書き込み [`IHtmlFormatter`](/slides/python-net/ja/aspose.slides.export/ihtmlformatter)。 |
| [`slide_image_format`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/slide_image_format/) | スライド画像形式オプションを取得または設定します。<br/>            読み取り/書き込み [`ISlideImageFormat`](/slides/python-net/ja/aspose.slides.export/islideimageformat)。 |
| [`show_hidden_slides`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/show_hidden_slides/) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。<br/>            デフォルトは `false` です。 |
| [`jpeg_quality`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/jpeg_quality/) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。<br/>            読み取り/書き込み **int**。 |
| [`pictures_compression`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/pictures_compression/) | 画像の圧縮レベルを表します。<br/>            読み取り/書き込み [`IHtmlOptions.pictures_compression`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/pictures_compression)。 |
| [`delete_pictures_cropped_areas`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/delete_pictures_cropped_areas/) | 切り抜かれた部分がドキュメントの一部として残るかどうかを示すブールフラグです。true の場合、切り抜かれた <br/>            部分は削除され、false の場合はドキュメントにシリアライズされます（これによりファイルが大きくなる可能性があります）。<br/>            読み取り/書き込み **bool**。 |
| [`svg_responsive_layout`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/svg_responsive_layout/) | SVG コンテナから幅と高さ属性を除外する場合は true に設定します - これによりレイアウトがレスポンシブになります。そうでない場合は false に設定します。<br/>            読み取り/書き込み **bool**。 |
| [`disable_font_ligatures`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/disable_font_ligatures/) | テキストが合字を使用せずにレンダーされるかどうかを示す値を取得または設定します。<br/>            `true` に設定すると、レンダー出力で合字が無効になります。デフォルトでは、このプロパティは `false` に設定されています。 |
| [`slides_layout_options`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/slides_layout_options/) | プレゼンテーション [`ISlidesLayoutOptions`](/slides/python-net/ja/aspose.slides.export/islideslayoutoptions) をエクスポートする際にスライドがページ上に配置されるモードを取得または設定します。 |
| [`ink_options`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/ink_options/) | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。<br/>            読み取り専用 [`IInkOptions`](/slides/python-net/ja/aspose.slides.export/iinkoptions) |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/warning_callback/) |  |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/progress_callback/) |  |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/default_regular_font/) |  |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/gradient_style/) |  |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/ihtmloptions/skip_java_script_links/) |  |

### 参照
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)