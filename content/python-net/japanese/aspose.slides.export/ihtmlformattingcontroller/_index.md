---
title: IHtmlFormattingController class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/ihtmlformattingcontroller/
---
## IHtmlFormattingController クラス

HTMLファイルの生成を制御します。

IHtmlFormattingController 型は以下のメンバーを公開します：

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/ja/aspose.slides.export/ihtmlformattingcontroller/write_document_start/#ihtmlgenerator-ipresentation) | html ドキュメントのヘッダーを書き込みます。プレゼンテーションの変換ごとに 1 回呼び出されます。 |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/ja/aspose.slides.export/ihtmlformattingcontroller/write_document_end/#ihtmlgenerator-ipresentation) | html ドキュメントのフッターを書き込みます。プレゼンテーションの変換ごとに 1 回呼び出されます。 |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/ja/aspose.slides.export/ihtmlformattingcontroller/write_slide_start/#ihtmlgenerator-islide) | html スライドのヘッダーを書き込みます。各スライドごとに 1 回呼び出されます。 |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/ja/aspose.slides.export/ihtmlformattingcontroller/write_slide_end/#ihtmlgenerator-islide) | html スライドのフッターを書き込みます。各スライドごとに 1 回呼び出されます。 |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/ja/aspose.slides.export/ihtmlformattingcontroller/write_shape_start/#ihtmlgenerator-ishape) | シェイプのレンダリング前に呼び出されます。各シェイプごとに 1 回呼び出されます。この関数がジェネレーターに何か書き込むと、現在のスライド画像の生成が完了し、追加された html フラグメントが挿入され、前の画像の上に新しい画像が開始されます。 |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/ja/aspose.slides.export/ihtmlformattingcontroller/write_shape_end/#ihtmlgenerator-ishape) | シェイプのレンダリング前に呼び出されます。各シェイプごとに 1 回呼び出されます。この関数がジェネレーターに何か書き込むと、現在のスライド画像の生成が完了し、追加された html フラグメントが挿入され、前の画像の上に新しい画像が開始されます。 |

### 参照
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)