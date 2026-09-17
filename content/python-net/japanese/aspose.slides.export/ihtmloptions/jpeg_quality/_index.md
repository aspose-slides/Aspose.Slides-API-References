---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## jpeg_quality プロパティ
PDF ドキュメント内の JPEG 画像の品質を決定する値を取得または設定します。
            読み書き **int**.

### 備考

ドキュメントに JPEG 画像が含まれている場合にのみ効果があります。

PDF 形式で保存するときに、ドキュメント内の画像の品質を取得または設定するためにこのプロパティを使用します。
            値は 0 から 100 の範囲で、0 は最悪の品質だが最大の圧縮、100 は最高の品質だが最小の圧縮を意味します。

既定値は **95** です。

### 定義:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```

### 参照
* クラス [`IHtmlOptions`](/slides/python-net/ja/aspose.slides.export/ihtmloptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)