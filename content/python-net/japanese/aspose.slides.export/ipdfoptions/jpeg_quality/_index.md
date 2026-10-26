---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.export/ipdfoptions/jpeg_quality/
weight: 150
---
## jpeg_quality プロパティ
PDF 文書内の JPEG 画像の品質を決定する値を取得または設定します。
            読み取り/書き込み **int**.

### 備考

ドキュメントに JPEG 画像が含まれている場合にのみ効果があります。

PDF 形式で保存する際に、ドキュメント内の画像の品質を取得または設定するためにこのプロパティを使用します。
            値は 0 から 100 の範囲で変化し、0 は最低品質で最大圧縮、100 は最高品質で最小圧縮を意味します。

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

### 参照
* クラス [`IPdfOptions`](/slides/python-net/ja/aspose.slides.export/ipdfoptions)
* モジュール [`aspose.slides.export`](/slides/python-net/ja/aspose.slides.export)
* ライブラリ [`Aspose.Slides`](/slides/python-net)