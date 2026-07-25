---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換するには true に設定します。bool を取得します。
type: docs
weight: 326
url: /ja/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() メソッド

true に設定すると、プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。**bool** を取得します。

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## 備考

デフォルトは **true** です。Pdf ドキュメントはベクターグラフィックとラスタ画像の両方を含むことができます。SaveMetafilesAsPng が **true** に設定されている場合、元の Metafile 画像は Png 形式に変換され、Pdf にラスタ画像として保存されます。SaveMetafilesAsPng が **false** に設定されている場合、元の Metafile は Pdf のベクターグラフィックに変換されます。各アプローチには利点と欠点があります。例えば、Metafile が PNG に変換されると、結果のドキュメントのスケーリング時に品質の低下が起こる可能性があります。Metafile が Pdf のベクターグラフィックに変換される場合、Pdf ビューアツールでパフォーマンスの問題が発生する可能性があります。

## 参照

* クラス [PdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)