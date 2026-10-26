---
title: get_JpegQuality()
second_title: Aspose.Slides for C++ API リファレンス
description: PDF ドキュメント内の JPEG 画像の品質を決定する値を返します。uint8_t を読み取ります。
type: docs
weight: 222
url: /ja/aspose.slides.export/pdfoptions/get_jpegquality/
---
## PdfOptions::get_JpegQuality() メソッド

PDF ドキュメント内の JPEG 画像の品質を決定する値を返します。**uint8_t** を読み取ります。

```cpp
uint8_t Aspose::Slides::Export::PdfOptions::get_JpegQuality() override
```

## 備考


この設定は、ドキュメントに JPEG 画像が含まれている場合にのみ有効です。

PDF 形式で保存する際に、ドキュメント内の画像の品質を取得または設定するためにこのプロパティを使用します。値は 0 から 100 の範囲で、0 は品質が最悪で圧縮率が最大、100 は品質が最高で圧縮率が最小を意味します。

デフォルト値は **100** です。

## 参照

* クラス [PdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)