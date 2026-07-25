---
title: set_BestImagesCompressionRatio()
second_title: Aspose.Slides for C++ API リファレンス
description: 各画像に対してデフォルトではなく最も効果的な圧縮を自動的に選択すべきかを示します。bool.true に設定すると、プレゼンテーション内のすべての画像について最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。
type: docs
weight: 105
url: /ja/aspose.slides.export/pdfoptions/set_bestimagescompressionratio/
---
## PdfOptions::set_BestImagesCompressionRatio(bool) メソッド


各画像に対して、デフォルトではなく最も効果的な圧縮を自動的に選択すべきかを示します。**bool**.true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。

```cpp
void Aspose::Slides::Export::PdfOptions::set_BestImagesCompressionRatio(bool value) override
```

## 備考


最適な画像圧縮率の選択は計算コストが高く、追加の RAM を必要とし、このオプションはデフォルトで **bool**.false です。

デフォルトは **bool**.false。 
## 参照

* クラス [PdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)