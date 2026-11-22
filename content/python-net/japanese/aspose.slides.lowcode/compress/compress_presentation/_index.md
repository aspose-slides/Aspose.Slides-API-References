---
title: compress_presentation method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
利用可能なすべての圧縮手順を適用してプレゼンテーションのサイズを縮小します:

* 未使用のマスタースライドを削除します **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* 未使用のレイアウトスライドを削除します **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* 埋め込みフォントで実際に使用されているグリフのみを保持します **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* 画像の解像度を150 DPIに下げ、画像のトリミング領域を削除します **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.

```python
@staticmethod
def compress_presentation(presentation):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/ja/aspose.slides/presentation) | 圧縮対象のプレゼンテーション。 |

### 備考

圧縮をカスタマイズするには、例えば別の画像解像度を使用したり手順をスキップしたりしたい場合は、上記のメソッドを個別に呼び出し、このメソッドを使用しないでください。画像のトリミング領域は永久に削除され、PowerPoint では復元できません。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` は `None` です。 |

### 参照
* クラス [`Compress`](/slides/python-net/ja/aspose.slides.lowcode/compress)
* クラス [`Presentation`](/slides/python-net/ja/aspose.slides/presentation)
* モジュール [`aspose.slides.lowcode`](/slides/python-net/ja/aspose.slides.lowcode)
* ライブラリ [`Aspose.Slides`](/slides/python-net)