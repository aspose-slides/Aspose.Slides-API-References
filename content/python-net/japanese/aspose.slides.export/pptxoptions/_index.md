---
title: PptxOptions class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/pptxoptions/
---
## PptxOptions クラス

OpenXml プレゼンテーション (PPTX, PPSX, POTX, PPTM, PPSM, POTM) の保存オプションを表します。

**Inheritance:**[`PptxOptions`](/slides/python-net/ja/aspose.slides.export/pptxoptions) → [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)

PptxOptions 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/pptxoptions/__init__/#) | PptxOptions の新しいインスタンスを作成します |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`warning_callback`](/slides/python-net/ja/aspose.slides.export/pptxoptions/warning_callback/) | 警告を受け取り、ロード処理を継続するか中止するかを決定するオブジェクトを取得または設定します。<br/>            読み書き [`IWarningCallback`](/slides/python-net/ja/aspose.slides.warnings/iwarningcallback). |
| [`progress_callback`](/slides/python-net/ja/aspose.slides.export/pptxoptions/progress_callback/) | 保存進行状況のパーセンテージ更新用コールバックオブジェクトを表します。<br/>            参照 [`IProgressCallback`](/slides/python-net/ja/aspose.slides/iprogresscallback). |
| [`default_regular_font`](/slides/python-net/ja/aspose.slides.export/pptxoptions/default_regular_font/) | ソースフォントが見つからない場合に使用されるフォントを取得または設定します。<br/>            読み書き **str**. |
| [`gradient_style`](/slides/python-net/ja/aspose.slides.export/pptxoptions/gradient_style/) | グラデーションのビジュアルスタイルを取得または設定します。<br/>            読み書き [`GradientStyle`](/slides/python-net/ja/aspose.slides/gradientstyle). |
| [`skip_java_script_links`](/slides/python-net/ja/aspose.slides.export/pptxoptions/skip_java_script_links/) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。 <br/>            読み書き **bool**. デフォルト値は **false** です。 |
| [`conformance`](/slides/python-net/ja/aspose.slides.export/pptxoptions/conformance/) | Presentation ドキュメントが準拠するコンフォーマンスクラスを指定します。<br/>            デフォルト値は [`Conformance.ECMA_376_2006`](/slides/python-net/ja/aspose.slides.export/conformance/ECMA_376_2006) |
| [`zip_64_mode`](/slides/python-net/ja/aspose.slides.export/pptxoptions/zip_64_mode/) | Presentation ドキュメントに ZIP64 形式を使用するかどうかを指定します。 <br/>            デフォルト値は [`Zip64Mode.IF_NECESSARY`](/slides/python-net/ja/aspose.slides.export/zip64mode/IF_NECESSARY) |
| [`refresh_thumbnail`](/slides/python-net/ja/aspose.slides.export/pptxoptions/refresh_thumbnail/) | プレゼンテーションのサムネイルを更新するかどうかを指定します。 <br/>            読み書き **bool**。<br/>            デフォルト値は **true** です。 |
| [`compression_level`](/slides/python-net/ja/aspose.slides.export/pptxoptions/compression_level/) | プレゼンテーションドキュメントを保存する際に使用される圧縮レベルを指定します。<br/>            デフォルト値は [`CompressionLevel.LEVEL6`](/slides/python-net/ja/aspose.slides.export/compressionlevel/LEVEL6)です。 |

### 参照
* クラス [`PptxOptions`](/slides/python-net/ja/aspose.slides.export/pptxoptions)
* クラス [`SaveOptions`](/slides/python-net/ja/aspose.slides.export/saveoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)