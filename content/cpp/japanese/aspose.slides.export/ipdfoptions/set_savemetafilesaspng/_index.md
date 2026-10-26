---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は true を設定します。bool を書き込みます。
type: docs
weight: 300
url: /ja/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) method


True を設定すると、プレゼンテーションで使用されるすべてのメタファイルが PNG 画像に変換されます。**bool** を書き込みます。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## 備考


デフォルトは **true** です。Pdf ドキュメントはベクター グラフィックスとラスター画像を含むことができます。SaveMetafilesAsPng が true に設定されている場合、ソースの Metafile 画像は Png 形式に変換され、Pdf にラスター画像として保存されます。SaveMetafilesAsPng が false に設定されている場合、ソースの Metafile は Pdf ベクター グラフィックスに変換されます。それぞれのアプローチには利点と欠点があります。例えば、Metafile が PNG に変換されると、結果のドキュメントのスケーリング時に品質の低下が発生する可能性があります。Metafile が Pdf ベクター グラフィックスに変換される場合、Pdf ビューア ツールでパフォーマンスの問題が発生する可能性があります。 
## 参照

* クラス [IPdfOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)