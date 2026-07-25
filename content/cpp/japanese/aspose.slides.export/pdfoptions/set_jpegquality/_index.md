---
title: set_JpegQuality()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: PDF ドキュメント内の JPEG 画像の品質を決定する値を設定します。uint8_tで書き込みます。
type: docs
weight: 235
url: /ja/aspose.slides.export/pdfoptions/set_jpegquality/
---
## PdfOptions::set_JpegQuality(uint8_t) メソッド


PDF ドキュメント内の JPEG 画像の品質を決定する値を設定します。**uint8_t** で書き込みます。

```cpp
void Aspose::Slides::Export::PdfOptions::set_JpegQuality(uint8_t value) override
```

## 備考


この設定は文書に JPEG 画像が含まれている場合にのみ有効です。

PDF 形式で保存する際、文書内の画像の品質を取得または設定するためにこのプロパティを使用します。値は 0 から 100 の範囲で、0 は最低の品質で最大圧縮、100 は最高の品質で最小圧縮を意味します。

デフォルト値は **100** です。
## 参照

* クラス [PdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)