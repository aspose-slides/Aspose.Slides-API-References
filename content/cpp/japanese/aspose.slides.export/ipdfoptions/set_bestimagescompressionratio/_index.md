---
title: set_BestImagesCompressionRatio()
second_title: Aspose.Slides for C++ API リファレンス
description: 各画像に対して、デフォルトの圧縮ではなく最も効果的な圧縮を自動的に選択すべきかどうかを示します。bool.true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。
type: docs
weight: 40
url: /ja/aspose.slides.export/ipdfoptions/set_bestimagescompressionratio/
---
## IPdfOptions::set_BestImagesCompressionRatio(bool) メソッド

各画像に対して最も効果的な圧縮（既定のものではなく）を自動的に選択すべきかどうかを示します。**bool**.true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_BestImagesCompressionRatio(bool value)=0
```

## 備考

最適な画像圧縮率の選択は計算コストが高く、追加の RAM が必要となり、このオプションはデフォルトで **bool**.false です。

デフォルトは **bool**.false です。 
## 参照

* クラス [IPdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)