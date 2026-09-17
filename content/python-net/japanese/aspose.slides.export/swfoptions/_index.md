---
title: SwfOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/swfoptions/
---
## SwfOptions クラス

Provides options that control how a presentation is saved in Swf format.

**Inheritance:**[`SwfOptions`](/slides/python-net/ja/aspose.slides.export/swfoptions) → [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)

SwfOptions 型は以下のメンバーを公開します：

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/swfoptions/__init__/#) | デフォルトコンストラクタ。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/swfoptions/warning_callback/) | 警告を受け取り、読み込みプロセスを続行するか中止するかを決定するオブジェクトを返すまたは設定します。<br/>            読み書き [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/swfoptions/progress_callback/) | 保存進行状況のパーセンテージ更新のためのコールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/swfoptions/default_regular_font/) | ソースフォントが見つからない場合に使用されるフォントを返すまたは設定します。<br/>            読み書き **str**。 |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/swfoptions/gradient_style/) | グラデーションの視覚スタイルを返すまたは設定します。<br/>            読み書き [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/swfoptions/skip_java_script_links/) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 <br/>            読み書き **bool**. デフォルト値は **false** です。 |
| [`show_hidden_slides`](/slides/python-net/ja/aspose.slides.export/swfoptions/show_hidden_slides/) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。<br/>            デフォルトは `false` です。 |
| [`compressed`](/slides/python-net/ja/aspose.slides.export/swfoptions/compressed/) | 生成された SWF ドキュメントを圧縮するかどうかを指定します。<br/>            デフォルトは `true` です。 |
| [`viewer_included`](/slides/python-net/ja/aspose.slides.export/swfoptions/viewer_included/) | 生成された SWF ドキュメントに統合ビューアーを含めるかどうかを指定します。<br/>            デフォルトは `true` です。 |
| [`show_page_border`](/slides/python-net/ja/aspose.slides.export/swfoptions/show_page_border/) | ページ周囲の境界線を表示するかどうかを指定します。デフォルトは true です。 |
| [`show_full_screen`](/slides/python-net/ja/aspose.slides.export/swfoptions/show_full_screen/) | 全画面表示ボタンを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| [`show_page_stepper`](/slides/python-net/ja/aspose.slides.export/swfoptions/show_page_stepper/) | ページステッパーを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| [`show_search`](/slides/python-net/ja/aspose.slides.export/swfoptions/show_search/) | 検索セクションを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| [`show_top_pane`](/slides/python-net/ja/aspose.slides.export/swfoptions/show_top_pane/) | 上部全体ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| [`show_bottom_pane`](/slides/python-net/ja/aspose.slides.export/swfoptions/show_bottom_pane/) | 下部ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| [`show_left_pane`](/slides/python-net/ja/aspose.slides.export/swfoptions/show_left_pane/) | 左側ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| [`start_open_left_pane`](/slides/python-net/ja/aspose.slides.export/swfoptions/start_open_left_pane/) | 左側ペインを開いた状態で開始します。flashvars で上書き可能です。デフォルトは false です。 |
| [`enable_context_menu`](/slides/python-net/ja/aspose.slides.export/swfoptions/enable_context_menu/) | コンテキストメニューを有効/無効にします。デフォルトは true です。 |
| [`logo_image_bytes`](/slides/python-net/ja/aspose.slides.export/swfoptions/logo_image_bytes/) | ビューアーの右上隅にロゴとして表示される画像。<br/>            画像は 32x64 ピクセルの PNG である必要があります。そうでない場合、ロゴが正しく表示されないことがあります。 |
| [`logo_link`](/slides/python-net/ja/aspose.slides.export/swfoptions/logo_link/) | ロゴの完全なハイパーリンクアドレスを取得または設定します。<br/>            [`SwfOptions.logo_image_bytes`](/slides/python-net/ja/aspose.slides.export/swfoptions/logo_image_bytes) が指定されている場合にのみ効果があります。 |
| [`jpeg_quality`](/slides/python-net/ja/aspose.slides.export/swfoptions/jpeg_quality/) | JPEG 画像の品質を指定します。<br/>            デフォルトは 95 です。 |
| [`slides_layout_options`](/slides/python-net/ja/aspose.slides.export/swfoptions/slides_layout_options/) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [`ISlidesLayoutOptions`](/slides/python-net/ja/aspose.slides.export/islideslayoutoptions)。<br/>            このプロパティは [`HandoutLayoutingOptions`](/slides/python-net/ja/aspose.slides.export/handoutlayoutingoptions) 型のオブジェクトの割り当てをサポートしません。 |

### 参照
* クラス [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)
* クラス [`SwfOptions`](/slides/python-net/ja/aspose.slides.export/swfoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)