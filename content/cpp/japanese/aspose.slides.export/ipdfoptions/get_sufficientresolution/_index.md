---
title: get_SufficientResolution()
second_title: Aspose.Slides for C++ API リファレンス
description: PDF ドキュメント内の画像の解像度を決定する値を返します。
type: docs
weight: 313
url: /ja/aspose.slides.export/ipdfoptions/get_sufficientresolution/
---
## IPdfOptions::get_SufficientResolution() メソッド


PDF ドキュメント内の画像の解像度を決定する値を返します。

```cpp
virtual float Aspose::Slides::Export::IPdfOptions::get_SufficientResolution()=0
```

## 備考


プロパティは、ファイルサイズ、エクスポート時間、および画像品質に影響します。

デフォルト値は **96**。

このパラメータの効果は、いくつかの要因に依存します。アルゴリズムは、プロパティの値、元画像のサイズ、および画像フレームのサイズに基づいて、最適な出力画像サイズを取得しようとします。類似のプロパティ値を使用すると同じ結果になる場合があります。目に見える効果を得るために、ステップ 16 または 32 を使用することを推奨します。

読み取り **float**. 
## 参照

* クラス [IPdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)