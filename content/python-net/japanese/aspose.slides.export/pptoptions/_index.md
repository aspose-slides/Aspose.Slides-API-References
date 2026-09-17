---
title: PptOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/pptoptions/
---
## PptOptions クラス

プレゼンテーションを PPT 形式で保存する方法を制御するオプションを提供します。

**継承:**[`PptOptions`](/slides/python-net/ja/aspose.slides.export/pptoptions) → [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)

PptOptions 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/pptoptions/__init__/#) |  |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/pptoptions/warning_callback/) | 警告を受け取り、ロード処理を継続するか中止するかを決定するオブジェクトを取得または設定します。<br/>            読み取り/書き込み [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/pptoptions/progress_callback/) | 保存の進行状況をパーセンテージで更新するコールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/pptoptions/default_regular_font/) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。<br/>            読み取り/書き込み **str**. |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/pptoptions/gradient_style/) | グラデーションのビジュアルスタイルを取得または設定します。<br/>            読み取り/書き込み [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/pptoptions/skip_java_script_links/) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。<br/>            読み取り/書き込み **bool**. デフォルト値は **false** です。 |
| [`root_directory_clsid`](/slides/python-net/ja/aspose.slides.export/pptoptions/root_directory_clsid/) | ルートディレクトリエントリに格納されるオブジェクトクラス GUID（CLSID）を表します。ドキュメントのアプリケーションの COM<br/>            アクティベーションに使用できます。<br/>            デフォルト値は '64818D11-4F9B-11CF-86EA-00AA00B929E8' で、'Microsoft Powerpoint.Slide.8' に対応します。 |


### 参照
* クラス [`PptOptions`](/slides/python-net/ja/aspose.slides.export/pptoptions)
* クラス [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)