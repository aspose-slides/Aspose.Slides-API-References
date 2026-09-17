---
title: SVGOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/svgoptions/
---
## SVGOptions クラス

SVG オプションを表します。

**継承:**[`SVGOptions`](/slides/python-net/ja/aspose.slides.export/svgoptions) → [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)

SVGOptions 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/svgoptions/__init__/#) | SVGOptions クラスの新しいインスタンスを初期化します。 |
| [`__init__(self, link_embed_controller)`](/slides/python-net/ja/aspose.slides.export/svgoptions/__init__/#ilinkembedcontroller) | リンク埋め込みコントローラオブジェクトを指定して、SVGOptions クラスの新しいインスタンスを初期化します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/svgoptions/warning_callback/) | 警告を受け取り、ロード処理を続行するか中止するかを決定するオブジェクトを取得または設定します。<br/>            読み書き [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/svgoptions/progress_callback/) | 進捗率の保存更新のためのコールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/svgoptions/default_regular_font/) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。<br/>            読み書き **str**。 |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/svgoptions/gradient_style/) | グラデーションのビジュアルスタイルを取得または設定します。<br/>            読み書き [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/svgoptions/skip_java_script_links/) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。<br/>            読み書き **bool**。デフォルト値は **false** です。 |
| [`ink_options`](/slides/python-net/ja/aspose.slides.export/svgoptions/ink_options/) | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。<br/>            読み取り専用 [`IInkOptions`](/slides/python-net/ja/aspose.slides.export/iinkoptions) |
| [`use_frame_size`](/slides/python-net/ja/aspose.slides.export/svgoptions/use_frame_size/) | テキストフレームをレンダリング領域に含めるかどうかを決定します。<br/>            読み書き **bool**。<br/>            デフォルト値は false です。 |
| [`use_frame_rotation`](/slides/python-net/ja/aspose.slides.export/svgoptions/use_frame_rotation/) | レンダリング時に指定された形状の回転を実行するかどうかを決定します。<br/>            読み書き **bool**。<br/>            デフォルト値は true です。 |
| [`vectorize_text`](/slides/python-net/ja/aspose.slides.export/svgoptions/vectorize_text/) | スライド上のテキストをグラフィックとして保存するかどうかを決定します。<br/>            読み書き **bool**。 |
| [`metafile_rasterization_dpi`](/slides/python-net/ja/aspose.slides.export/svgoptions/metafile_rasterization_dpi/) | メタファイルのラスター化における下限解像度を取得または設定します。<br/>            読み書き **int**。 |
| [`disable_3d_text`](/slides/python-net/ja/aspose.slides.export/svgoptions/disable_3d_text/) | SVG で 3D テキストを無効にするかどうかを決定します。<br/>            読み書き **bool**。 |
| [`disable_gradient_split`](/slides/python-net/ja/aspose.slides.export/svgoptions/disable_gradient_split/) | FromCornerX および FromCenter グラデーションの分割を無効にします。<br/>            読み書き **bool**。 |
| [`disable_line_end_cropping`](/slides/python-net/ja/aspose.slides.export/svgoptions/disable_line_end_cropping/) | SVG 1.1 ではマーカーのインセットを定義する機能がありません。<br/>            Aspose.Slides の SVG ライティングエンジンはその問題への回避策を提供しています：<br/>            矢印付きの行末をクロップし、行がマーカーと重ならないようにします。<br/>            このオプションはその動作をオフにします。<br/>            読み書き **bool**。 |
| [`default`](/slides/python-net/ja/aspose.slides.export/svgoptions/default/) | デフォルト設定を取得します。<br/>            読み取り専用 [`SVGOptions`](/slides/python-net/ja/aspose.slides.export/svgoptions)。 |
| [`simple`](/slides/python-net/ja/aspose.slides.export/svgoptions/simple/) | 最もシンプルで小さい SVG ファイル生成の設定を取得します。<br/>            読み取り専用 [`SVGOptions`](/slides/python-net/ja/aspose.slides.export/svgoptions)。 |
| [`wysiwyg`](/slides/python-net/ja/aspose.slides.export/svgoptions/wysiwyg/) | 最も正確な SVG ファイル生成の設定を取得します。<br/>            読み取り専用 [`SVGOptions`](/slides/python-net/ja/aspose.slides.export/svgoptions)。 |
| [`jpeg_quality`](/slides/python-net/ja/aspose.slides.export/svgoptions/jpeg_quality/) | JPEG エンコード品質を決定します。<br/>            読み書き **int**。 |
| [`shape_formatting_controller`](/slides/python-net/ja/aspose.slides.export/svgoptions/shape_formatting_controller/) | ユーザーが形状変換を制御できるコールバックインターフェイスを取得および設定します。<br/>            読み書き [`ISvgShapeFormattingController`](/slides/python-net/ja/aspose.slides.export/isvgshapeformattingcontroller)。 |
| [`pictures_compression`](/slides/python-net/ja/aspose.slides.export/svgoptions/pictures_compression/) | 画像の圧縮レベルを表します |
| [`delete_pictures_cropped_areas`](/slides/python-net/ja/aspose.slides.export/svgoptions/delete_pictures_cropped_areas/) | クロップされた部分が文書の一部として残るかどうかを示すブールフラグです。true の場合、クロップされた部分は削除され、false の場合は文書にシリアライズされます（これによりファイルが大きくなる可能性があります）。 |
| [`external_fonts_handling`](/slides/python-net/ja/aspose.slides.export/svgoptions/external_fonts_handling/) | 外部ロードされたフォントの処理方法を決定します。<br/>            読み書き [`SvgExternalFontsHandling`](/slides/python-net/ja/aspose.slides.export/svgexternalfontshandling)。 |
| [`disable_font_ligatures`](/slides/python-net/ja/aspose.slides.export/svgoptions/disable_font_ligatures/) | テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得または設定します。<br/>            `true` に設定すると、合字はレンダリング出力で無効になります。デフォルトではこのプロパティは `false` に設定されています。 |

### 参照
* クラス [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)
* クラス [`SVGOptions`](/slides/python-net/ja/aspose.slides.export/svgoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)