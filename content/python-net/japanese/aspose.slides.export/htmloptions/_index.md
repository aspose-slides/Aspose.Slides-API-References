---
title: HtmlOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/htmloptions/
---
## HtmlOptions クラス

HTML エクスポートオプションを表します。

**継承:**[`HtmlOptions`](/slides/python-net/ja/aspose.slides.export/htmloptions) → [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)

HtmlOptions 型は次のメンバーを公開します：

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, link_embed_controller)`](/slides/python-net/ja/aspose.slides.export/htmloptions/__init__/#ilinkembedcontroller) | コールバックを指定した新しい HtmlOptions オブジェクトを作成します。 |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/htmloptions/__init__/#) | 単一の HTML ファイルに保存するための新しい HtmlOptions オブジェクトを作成します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/htmloptions/warning_callback/) | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。<br/>            読み取り/書き込み [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/htmloptions/progress_callback/) | 保存進行状況のパーセンテージ更新のためのコールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/htmloptions/default_regular_font/) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。<br/>            読み取り/書き込み **str**。 |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/htmloptions/gradient_style/) | グラデーションの視覚スタイルを取得または設定します。<br/>            読み取り/書き込み [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/htmloptions/skip_java_script_links/) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。<br/>            読み取り/書き込み **bool**。既定値は **false** です。 |
| [`slides_layout_options`](/slides/python-net/ja/aspose.slides.export/htmloptions/slides_layout_options/) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [`ISlidesLayoutOptions`](/slides/python-net/ja/aspose.slides.export/islideslayoutoptions)。 |
| [`ink_options`](/slides/python-net/ja/aspose.slides.export/htmloptions/ink_options/) | エクスポートドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。<br/>            読み取り専用 [`IInkOptions`](/slides/python-net/ja/aspose.slides.export/iinkoptions) |
| [`show_hidden_slides`](/slides/python-net/ja/aspose.slides.export/htmloptions/show_hidden_slides/) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。<br/>            デフォルトは `false` です。 |
| [`html_formatter`](/slides/python-net/ja/aspose.slides.export/htmloptions/html_formatter/) | HTML テンプレートを取得または設定します。<br/>            読み取り/書き込み [`IHtmlFormatter`](/slides/python-net/ja/aspose.slides.export/ihtmlformatter)。 |
| [`disable_font_ligatures`](/slides/python-net/ja/aspose.slides.export/htmloptions/disable_font_ligatures/) | テキストを合字を使用せずにレンダリングするかどうかを示す値を取得または設定します。<br/>            `true` に設定すると、レンダリング出力で合字が無効になります。既定では、このプロパティは `false` に設定されています。 |
| [`slide_image_format`](/slides/python-net/ja/aspose.slides.export/htmloptions/slide_image_format/) | スライド画像形式オプションを取得または設定します。<br/>            読み取り/書き込み [`ISlideImageFormat`](/slides/python-net/ja/aspose.slides.export/islideimageformat)。 |
| [`jpeg_quality`](/slides/python-net/ja/aspose.slides.export/htmloptions/jpeg_quality/) | PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。<br/>            読み取り/書き込み **int**。 |
| [`pictures_compression`](/slides/python-net/ja/aspose.slides.export/htmloptions/pictures_compression/) | 画像圧縮レベルを表します。 |
| [`delete_pictures_cropped_areas`](/slides/python-net/ja/aspose.slides.export/htmloptions/delete_pictures_cropped_areas/) | 切り取られた部分をドキュメントの一部として保持するかどうかを示すブールフラグです。true の場合、切り取られた<br/>            部分は削除され、false の場合はドキュメントにシリアライズされます（これによりファイルが大きくなる可能性があります）。 |
| [`svg_responsive_layout`](/slides/python-net/ja/aspose.slides.export/htmloptions/svg_responsive_layout/) | 幅と高さの属性を SVG コンテナから除外する場合は true に設定します。これによりレイアウトがレスポンシブになります。false の場合は除外しません。<br/>            読み取り/書き込み **bool**。 |

### 参照
* クラス [`HtmlOptions`](/slides/python-net/ja/aspose.slides.export/htmloptions)
* クラス [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)