---
title: Compress class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.lowcode/compress/
---
## Compress クラス

[`Presentation`](/slides/python-net/ja/aspose.slides/presentation) の圧縮を目的としたメソッドのグループを表します。

Compress 型は次のメンバーを公開します。

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`compress_presentation(presentation)`](/slides/python-net/ja/aspose.slides.lowcode/compress/compress_presentation/#presentation) | 利用可能なすべての圧縮手順を適用してプレゼンテーションのサイズを削減します：<br/>            <br/>* 未使用のマスタースライドを削除します **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.<br/>* 未使用のレイアウトスライドを削除します **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.<br/>* 埋め込みフォントで実際に使用されているグリフのみを保持します **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.<br/>* 画像の解像度を150 DPIに下げ、画像のトリミング領域を削除します **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**. |
| [`remove_unused_master_slides(pres)`](/slides/python-net/ja/aspose.slides.lowcode/compress/remove_unused_master_slides/#presentation) | 未使用のマスタースライドを削除して [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) を圧縮します。 |
| [`remove_unused_layout_slides(pres)`](/slides/python-net/ja/aspose.slides.lowcode/compress/remove_unused_layout_slides/#presentation) | 未使用のレイアウトスライドを削除して [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) を圧縮します。 |
| [`compress_embedded_fonts(pres)`](/slides/python-net/ja/aspose.slides.lowcode/compress/compress_embedded_fonts/#presentation) | 埋め込みフォントから未使用の文字を削除して [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) を圧縮します。 |
| [`compress_images(presentation, resolution)`](/slides/python-net/ja/aspose.slides.lowcode/compress/compress_images/#ipresentation-asposeslidesexportpicturescompression) | プレゼンテーション内の画像の解像度を下げ、トリミングされた領域を削除します、<br/>            PowerPoint の「画像の圧縮」と同様にすべての画像に適用されます。<br/>            スライド、レイアウトスライド、マスタースライド上の画像が処理され、グループシェイプ内の画像やシェイプの画像塗りつぶしも含まれます。 |

### 参照
* クラス [`Presentation`](/slides/python-net/ja/aspose.slides/presentation)
* モジュール [`aspose.slides.lowcode`](/slides/python-net/ja/aspose.slides.lowcode)
* ライブラリ [`Aspose.Slides`](/slides/python-net)