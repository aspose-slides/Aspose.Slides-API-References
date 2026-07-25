---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API リファレンス
description: True は、プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。bool を読み取ります。
type: docs
weight: 287
url: /ja/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() メソッド

True は、プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。**bool** を読み取ります。

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```
## 備考

デフォルトは **true** です。Pdf ドキュメントにはベクター グラフィックとラスタ 画像を含めることができます。SaveMetafilesAsPng が true に設定されている場合、ソース Metafile 画像は Png 形式に変換され、Pdf にラスタ画像として保存されます。SaveMetafilesAsPng が false に設定されている場合、ソース Metafile は Pdf のベクター グラフィックに変換されます。それぞれのアプローチには利点と欠点があります。例えば、Metafile が PNG に変換されると、結果のドキュメントの拡大縮小時に品質の低下が発生する可能性があります。Metafile が Pdf のベクター グラフィックに変換される場合、Pdf ビューアツールでパフォーマンスの問題が発生する可能性があります。

## 参照

* クラス [IPdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)