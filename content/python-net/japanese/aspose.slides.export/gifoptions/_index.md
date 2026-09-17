---
title: GifOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/gifoptions/
---
## GifOptions クラス

GIF エクスポート オプションを表します。

**継承:**[`GifOptions`](/slides/python-net/ja/aspose.slides.export/gifoptions) → [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)

GifOptions 型は以下のメンバーを公開しています。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/gifoptions/__init__/#) | GifOptions クラスの新しいインスタンスを初期化します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/gifoptions/warning_callback/) | 警告を受け取り、ロードプロセスを続行するか中止するかを決定するオブジェクトを取得または設定します。<br/>            読み取り/書き込み [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/gifoptions/progress_callback/) | 進捗率の更新を保存するためのコールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/gifoptions/default_regular_font/) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。<br/>            読み取り/書き込み **str**. |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/gifoptions/gradient_style/) | グラデーションの視覚スタイルを取得または設定します。<br/>            読み取り/書き込み [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/gifoptions/skip_java_script_links/) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。<br/>            読み取り/書き込み **bool**. デフォルト値は **false** です。 |
| [`frame_size`](/slides/python-net/ja/aspose.slides.export/gifoptions/frame_size/) | フレームサイズを取得または設定します。 |
| [`export_hidden_slides`](/slides/python-net/ja/aspose.slides.export/gifoptions/export_hidden_slides/) | 非表示スライドをエクスポートするかどうかを決定します。<br/>            デフォルト値は false です。 |
| [`transition_fps`](/slides/python-net/ja/aspose.slides.export/gifoptions/transition_fps/) | 遷移の FPS [frames/sec] を取得または設定します。<br/>            デフォルト値は 25 です。 |
| [`default_delay`](/slides/python-net/ja/aspose.slides.export/gifoptions/default_delay/) | デフォルトの遅延時間 [ms] を取得または設定します。[`ISlideShowTransition.advance_after_time`](/slides/python-net/ja/aspose.slides/islideshowtransition/advance_after_time) が設定されていない場合にこの値が使用されます。<br/>            デフォルト値は 1000 です。 |

### 参照
* クラス [`GifOptions`](/slides/python-net/ja/aspose.slides.export/gifoptions)
* クラス [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)