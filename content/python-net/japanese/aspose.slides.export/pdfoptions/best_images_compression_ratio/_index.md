---
title: best_images_compression_ratio property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/pdfoptions/best_images_compression_ratio/
weight: 60
---
## best_images_compression_ratio プロパティ
各画像に対してデフォルトではなく、最も効果的な圧縮（デフォルトのものではなく）を自動的に選択するかどうかを示します。  
**bool**.true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果として生成される PDF 文書のサイズが小さくなります。  
最も高い画像圧縮率の選択は計算コストが高く、追加の RAM を使用します。このオプションはデフォルトで **bool**.false です。


### 備考

デフォルトは **bool**.false です。

### 定義:
```python
@property
def best_images_compression_ratio(self):
    ...

@best_images_compression_ratio.setter
def best_images_compression_ratio(self, value):
    ...
```


### 参照
* クラス [`PdfOptions`](/slides/python-net/ja/aspose.slides.export/pdfoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)