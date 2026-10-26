---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true に設定します。bool を書き込みます。
type: docs
weight: 339
url: /ja/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) メソッド

プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true に設定します。**bool**を書き込みます。

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## 備考

デフォルトは **true** です。Pdf ドキュメントはベクター グラフィックとラスタ 画像を含むことができます。SaveMetafilesAsPng が true に設定されている場合、元の Metafile 画像は Png 形式に変換され、Pdf にラスタ画像として保存されます。SaveMetafilesAsPng が false に設定されている場合、元の Metafile は Pdf のベクター グラフィックに変換されます。それぞれのアプローチには利点と欠点があります。例えば、Metafile が PNG に変換されると、結果のドキュメントのスケーリング時に品質の低下が発生する可能性があります。Metafile が Pdf ベクター グラフィックに変換される場合、Pdf ビューアツールでパフォーマンスの問題が発生する可能性があります。

## 参照

* クラス [PdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)