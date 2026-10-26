---
title: save_metafiles_as_png property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png プロパティ
プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換するには true を設定します。
            読み取り/書き込み **bool**。


### 備考

デフォルトは **true** です。
            Pdf ドキュメントはベクター グラフィックとラスタ 画像を含むことができます。 
            SaveMetafilesAsPng が true に設定されている場合、元の Metafile 
            画像は Png 形式に変換され、Pdf にラスタ 画像として保存されます。 SaveMetafilesAsPng が false に設定されている場合、元の Metafile 
            は Pdf ベクター グラフィックに変換されます。各アプローチには利点と 
            欠点があります。例えば、Metafile が PNG に変換される場合、 
            結果の 
            ドキュメント スケーリング中に品質低下が発生する可能性があります。 Metafile が Pdf ベクター グラフィックに変換される場合、 
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
* クラス [`IPdfOptions`](/slides/python-net/ja/aspose.slides.export/ipdfoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)