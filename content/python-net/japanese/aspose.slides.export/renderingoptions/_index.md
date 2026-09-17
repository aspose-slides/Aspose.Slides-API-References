---
title: RenderingOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/renderingoptions/
---
## RenderingOptions クラス

プレゼンテーション/スライドがどのようにレンダリングされるかを制御するオプションを提供します。

**継承:**[`RenderingOptions`](/slides/python-net/ja/aspose.slides.export/renderingoptions) → [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)

RenderingOptions 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/renderingoptions/__init__/#) | デフォルトコンストラクタ。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/renderingoptions/warning_callback/) | 警告を受け取り、ロード処理を続行するか中止するかを決定するオブジェクトを取得または設定します。<br/>            読み取り/書き込み [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/renderingoptions/progress_callback/) | パーセンテージ単位で進捗更新を保存するためのコールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/renderingoptions/default_regular_font/) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。<br/>            読み取り/書き込み **str**. |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/renderingoptions/gradient_style/) | グラデーションのビジュアルスタイルを取得または設定します。<br/>            読み取り/書き込み [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/renderingoptions/skip_java_script_links/) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 <br/>            読み取り/書き込み **bool**. デフォルト値は **false** です。 |
| [`slides_layout_options`](/slides/python-net/ja/aspose.slides.export/renderingoptions/slides_layout_options/) | プレゼンテーション [`ISlidesLayoutOptions`](/slides/python-net/ja/aspose.slides.export/islideslayoutoptions) をエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します。 |
| [`ink_options`](/slides/python-net/ja/aspose.slides.export/renderingoptions/ink_options/) | エクスポートされたドキュメント内の Ink オブジェクトの外観を制御するオプションを提供します。<br/>            読み取り専用 [`IInkOptions`](/slides/python-net/ja/aspose.slides.export/iinkoptions) |
| [`disable_font_ligatures`](/slides/python-net/ja/aspose.slides.export/renderingoptions/disable_font_ligatures/) | テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得または設定します。<br/>            `true` に設定すると、レンダリング出力で合字が無効になります。デフォルトでは、このプロパティは `false` に設定されています。 |

### 関連項目
* クラス [`RenderingOptions`](/slides/python-net/ja/aspose.slides.export/renderingoptions)
* クラス [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)