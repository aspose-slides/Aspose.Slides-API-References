---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/pdfoptions/jpeg_quality/
weight: 160
---
## jpeg_quality プロパティ
PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。
            読み書き **int**.

### 備考

文書に JPEG 画像が含まれている場合にのみ効果があります。

PDF 形式で保存する際に、文書内の画像の品質を取得または設定するためにこのプロパティを使用します。
            この値は 0 から 100 の範囲で変化し、0 は品質が最悪で圧縮率が最大、100 は品質が最高で圧縮率が最小を意味します。

デフォルト値は **100** です。

### 定義:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```

### 関連項目
* クラス [`PdfOptions`](/slides/python-net/ja/aspose.slides.export/pdfoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)