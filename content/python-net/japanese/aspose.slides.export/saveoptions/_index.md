---
title: SaveOptions class
second_title: .NET 経由の Python 用 Aspose.Slides API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/saveoptions/
---
## SaveOptions クラス

抽象クラスで、プレゼンテーションの保存方法を制御するオプションを提供します。

SaveOptions 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/saveoptions/warning_callback/) | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。<br/>            読み書き [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/saveoptions/progress_callback/) | 保存の進捗更新（パーセンテージ）を受け取るコールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/saveoptions/default_regular_font/) | ソースフォントが見つからない場合に使用するフォントを取得または設定します。<br/>            読み書き **str**. |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/saveoptions/gradient_style/) | グラデーションの視覚スタイルを取得または設定します。<br/>            読み書き [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/saveoptions/skip_java_script_links/) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 <br/>            読み書き **bool**. デフォルト値は **false** . |

### 参照
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)