---
title: get_SufficientResolution()
second_title: Aspose.Slides for C++ API リファレンス
description: PDF ドキュメント内の画像の解像度を決定する値を返します。
type: docs
weight: 352
url: /ja/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() メソッド

PDF ドキュメント内の画像の解像度を決定する値を返します。

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## 備考

プロパティはファイルサイズ、エクスポート時間、画像品質に影響します。

デフォルト値は **96** です。

このパラメータの効果は、いくつかの要因に依存します。アルゴリズムは、プロパティ値、元画像サイズ、画像フレームサイズに基づいて最適な出力画像サイズを取得しようとします。類似したプロパティ値を使用すると、同じ結果になることがあります。目に見える効果を得るために、ステップ 16 または 32 を使用することを推奨します。

読み取り **float**。

## 参照

* クラス [PdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)