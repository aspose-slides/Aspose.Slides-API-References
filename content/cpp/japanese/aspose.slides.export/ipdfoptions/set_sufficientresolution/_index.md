---
title: set_SufficientResolution()
second_title: Aspose.Slides for C++ API リファレンス
description: PDF ドキュメント内の画像の解像度を決定する値を設定します。
type: docs
weight: 326
url: /ja/aspose.slides.export/ipdfoptions/set_sufficientresolution/
---
## IPdfOptions::set_SufficientResolution(float) メソッド


PDF ドキュメント内の画像の解像度を決定する値を設定します。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SufficientResolution(float value)=0
```

## 備考


プロパティはファイルサイズ、エクスポート時間、画像品質に影響します。

デフォルト値は **96** です。

このパラメータの効果は、いくつかの要因に依存します。アルゴリズムは、プロパティ値、ソース画像サイズ、画像フレームサイズに基づいて最適な出力画像サイズを取得しようとします。類似のプロパティ値を使用すると同じ結果になる場合があります。目に見える効果を得るために、ステップ 16 または 32 の使用が推奨されます。

書き込み **float**。 
## 参照

* クラス [IPdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)