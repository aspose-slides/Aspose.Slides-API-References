---
title: save_metafiles_as_png property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png プロパティ
True to convert all metafiles used in a presentation to the PNG images.
            読み書き **bool**.

### 備考

Default is **true** .
            Pdf ドキュメントにはベクター グラフィックとラスタ 画像を含めることができます。 
            SaveMetafilesAsPng が true に設定されている場合、ソース Metafile 
            画像は Png 形式に変換され、Pdf にラスタ 画像として保存されます。 
            SaveMetafilesAsPng が false に設定されている場合、ソース Metafile 
            は Pdf ベクター グラフィックに変換されます。各アプローチには利点と 
            欠点があります。例えば、Metafile が PNG に変換された場合、 
            結果としてのドキュメントのスケーリング中に品質低下が発生する可能性があります。 
            Metafile が Pdf ベクター グラフィックに変換された場合、 
            Pdf ビューアツールでパフォーマンスの問題が発生する可能性があります。

### 定義:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### 参照
* クラス [`PdfOptions`](/slides/python-net/ja/aspose.slides.export/pdfoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)