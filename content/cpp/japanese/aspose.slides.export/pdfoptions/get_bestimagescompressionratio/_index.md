---
title: get_BestImagesCompressionRatio()
second_title: Aspose.Slides for C++ API リファレンス
description: 各画像に対して、デフォルトの圧縮ではなく最も効果的な圧縮を自動的に選択するかどうかを示します。bool.true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。
type: docs
weight: 92
url: /ja/aspose.slides.export/pdfoptions/get_bestimagescompressionratio/
---
## PdfOptions::get_BestImagesCompressionRatio() メソッド

各画像に対して、デフォルトの圧縮ではなく最も効果的な圧縮を自動的に選択するかどうかを示します。**bool**.true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。

```cpp
bool Aspose::Slides::Export::PdfOptions::get_BestImagesCompressionRatio() override
```

## 備考

最適な画像圧縮率の選択は計算コストが高く、追加の RAM を消費します。このオプションはデフォルトで **bool**.false です。

デフォルトは **bool**.false です。

## 参照

* クラス [PdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)