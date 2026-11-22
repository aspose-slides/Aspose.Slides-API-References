---
title: compress_images method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.lowcode/compress/compress_images/
weight: 20
---
## compress_images(presentation, resolution) {#ipresentation-asposeslidesexportpicturescompression}
プレゼンテーション内の画像の解像度を下げ、トリミングされた領域を削除します。  
PowerPoint の「画像の圧縮」をすべての画像に適用したものと同様です。  
スライド、レイアウトスライド、マスタースライド上の画像が処理対象となり、グループシェイプ内の画像やシェイプの画像塗りつぶしも含まれます。

```python
@staticmethod
def compress_images(presentation, resolution):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation) | 処理対象のプレゼンテーション。 |
| resolution | [`PicturesCompression`](/slides/python-net/ja/aspose.slides.export/picturescompression) | 各画像が表示されるサイズに対する目標解像度。<br/><br/>[`PicturesCompression.DOCUMENT_RESOLUTION`](/slides/python-net/ja/aspose.slides.export/picturescompression/DOCUMENT_RESOLUTION) は画像を変更しません。 |

### 備考

目標解像度以下の画像は変更されません。画像は決して拡大されません。

処理対象外: スライドの背景、テーブルセルの塗り、チャート、SmartArt、GIF画像（アニメーションを保持するため）、SVG およびメタファイル（EMF/WMF）画像。

トリミングされた領域は永久に削除され、PowerPoint で復元できません。

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` は `None` です。 |

### 参照
* クラス [`Compress`](/slides/python-net/ja/aspose.slides.lowcode/compress)
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* 列挙型 [`PicturesCompression`](/slides/python-net/ja/aspose.slides.export/picturescompression)
* モジュール [`aspose.slides.lowcode`](/slides/python-net/ja/aspose.slides.lowcode)
* ライブラリ [`Aspose.Slides`](/slides/python-net)