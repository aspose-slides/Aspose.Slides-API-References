---
title: XpsOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/xpsoptions/
---
## XpsOptions クラス

Provides options that control how a presentation is saved in XPS format.

**継承:**[`XpsOptions`](/slides/python-net/ja/aspose.slides.export/xpsoptions) → [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)

XpsOptions 型は次のメンバーを公開します:

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/xpsoptions/__init__/#) | デフォルトコンストラクタ。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/xpsoptions/warning_callback/) | 警告を受け取り、ロードプロセスを続行するか中止するかを判断するオブジェクトを取得または設定します。<br/>            読み書き [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback)。 |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/xpsoptions/progress_callback/) | パーセンテージで保存の進行状況更新を行うコールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback)。 |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/xpsoptions/default_regular_font/) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。<br/>            読み書き **str**。 |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/xpsoptions/gradient_style/) | グラデーションの視覚スタイルを取得または設定します。<br/>            読み書き [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle)。 |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/xpsoptions/skip_java_script_links/) | プレゼンテーションを保存するときに、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 <br/>            読み書き **bool**. デフォルト値は **false** です。 |
| [`show_hidden_slides`](/slides/python-net/ja/aspose.slides.export/xpsoptions/show_hidden_slides/) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。<br/>            デフォルトは `false` です。 |
| [`save_metafiles_as_png`](/slides/python-net/ja/aspose.slides.export/xpsoptions/save_metafiles_as_png/) | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true に設定します。<br/>            読み書き **bool**。 |
| [`draw_slides_frame`](/slides/python-net/ja/aspose.slides.export/xpsoptions/draw_slides_frame/) | 各スライドの周囲に黒いフレームを描画する場合は true に設定します。<br/>             読み書き **bool**。 |

### 関連項目
* クラス [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)
* クラス [`XpsOptions`](/slides/python-net/ja/aspose.slides.export/xpsoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)