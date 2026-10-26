---
title: EmbedAllFontsHtmlController class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/embedallfontshtmlcontroller/
---
## EmbedAllFontsHtmlController クラス

WOFF 形式でプレゼンテーションのすべてのフォントを埋め込むために使用する書式制御クラスです。

EmbedAllFontsHtmlController 型は次のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller/__init__/#) | 新しいインスタンスを作成します |
| [`__init__(self, font_name_exclude_list)`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller/__init__/#liststr) | 新しいインスタンスを作成します |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`write_document_start(self, generator, presentation)`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller/write_document_start/#ihtmlgenerator-ipresentation) | HTML ドキュメントのヘッダーを書き込むために呼び出されます。プレゼンテーション変換ごとに一度呼び出されます。 |
| [`write_document_end(self, generator, presentation)`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller/write_document_end/#ihtmlgenerator-ipresentation) | HTML ドキュメントのフッターを書き込むために呼び出されます。プレゼンテーション変換ごとに一度呼び出されます。 |
| [`write_slide_start(self, generator, slide)`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller/write_slide_start/#ihtmlgenerator-islide) | HTML スライドのヘッダーを書き込むために呼び出されます。各スライドにつき一度呼び出されます。 |
| [`write_slide_end(self, generator, slide)`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller/write_slide_end/#ihtmlgenerator-islide) | HTML スライドのフッターを書き込むために呼び出されます。各スライドにつき一度呼び出されます。 |
| [`write_shape_start(self, generator, shape)`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller/write_shape_start/#ihtmlgenerator-ishape) | シェイプの描画前に呼び出されます。各シェイプにつき一度呼び出されます。この関数がジェネレータに何かを書き込むと、現在のスライド画像の生成が完了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。 |
| [`write_shape_end(self, generator, shape)`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller/write_shape_end/#ihtmlgenerator-ishape) | シェイプの描画前に呼び出されます。各シェイプにつき一度呼び出されます。この関数がジェネレータに何かを書き込むと、現在のスライド画像の生成が完了し、追加された HTML フラグメントが挿入され、前の画像の上に新しい画像が開始されます。 |
| [`write_all_fonts(self, generator, presentation)`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller/write_all_fonts/#ihtmlgenerator-ipresentation) | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) に含まれるすべてのフォントを書き込みます。 |
| [`write_font(self, generator, original_font, substituted_font, font_style, font_weight, font_data)`](/slides/python-net/ja/aspose.slides.export/embedallfontshtmlcontroller/write_font/#ihtmlgenerator-ifontdata-ifontdata-str-str-bytes) | データを base64 として HTML ドキュメント自体に書き込みます |


### 参照
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)