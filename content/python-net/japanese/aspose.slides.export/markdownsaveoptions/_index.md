---
title: MarkdownSaveOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions クラス

プレゼンテーションを Markdown に保存する方法を制御するオプションを表します。

**継承:**[`MarkdownSaveOptions`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions) → [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)

MarkdownSaveOptions 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/__init__/#) | コンストラクタ。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/warning_callback/) | 警告を受け取り、ロードプロセスを継続するか中止するかを判断するオブジェクトを取得または設定します。<br/>            読み書き [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/progress_callback/) | 保存進捗をパーセンテージで更新するコールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/default_regular_font/) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。<br/>            読み書き **str**. |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/gradient_style/) | グラデーションの視覚スタイルを取得または設定します。<br/>            読み書き [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/skip_java_script_links/) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするか指定します。 <br/>            読み書き **bool**. デフォルト値は **false** です。 |
| [`export_type`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/export_type/) | プレゼンテーションを変換する Markdown の仕様を指定します。<br/>            デフォルトは `TextOnly` です。 |
| [`base_path`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/base_path/) | リソースを含むドキュメントが保存されるベースパスを指定します。<br/>            デフォルトはアプリケーションの現在のディレクトリです。 |
| [`images_save_folder_name`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/images_save_folder_name/) | 画像を保存するフォルダー名を指定します。<br/>            デフォルトは `Images` です。 |
| [`new_line_type`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/new_line_type/) | 生成されたドキュメントが新しい改行コード \\r（Macintosh）か \\n（Unix）か \\r\\n（Windows）を使用するかを指定します。<br/>            デフォルトは `Unix` です。 |
| [`show_comments`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/show_comments/) | 生成されたドキュメントがコメントを表示するかどうかを指定します。<br/>            デフォルトは `false` です。 |
| [`show_hidden_slides`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/show_hidden_slides/) | 生成されたドキュメントが非表示スライドを含むかどうかを指定します。<br/>            デフォルトは `false` です。 |
| [`show_slide_number`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/show_slide_number/) | 生成されたドキュメントが各スライドの番号を表示するかどうかを指定します。<br/>            デフォルトは `false` です。 |
| [`flavor`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/flavor/) | プレゼンテーションを変換する Markdown の仕様を指定します。<br/>            デフォルトは `Multi-markdown` です。 |
| [`slide_number_format`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/slide_number_format/) | Markdown 出力のスライド番号ヘッダーに使用される書式文字列を取得または設定します。<br/>            書式には "{0}" プレースホルダーを含める必要があり、エクスポート時にスライドインデックスに置き換えられます。<br/>            例: "# Slide {0}" は "# Slide 1", "# Slide 2" などを生成します。 |
| [`handle_repeated_spaces`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/handle_repeated_spaces/) |  |
| [`remove_empty_lines`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions/remove_empty_lines/) | `true` に設定すると、最終的な Markdown 出力から空行または空白のみの行が削除されます。<br/>            デフォルトは `false` です。 |

### 参照
* クラス [`MarkdownSaveOptions`](/slides/python-net/ja/aspose.slides.export/markdownsaveoptions)
* クラス [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)