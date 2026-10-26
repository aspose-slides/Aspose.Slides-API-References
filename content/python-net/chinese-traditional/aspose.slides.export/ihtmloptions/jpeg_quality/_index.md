---
title: jpeg_quality property
second_title: Aspose.Slides 用於 Python 的 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/ihtmloptions/jpeg_quality/
weight: 80
---
## jpeg_quality 屬性
傳回或設定決定 PDF 文件中 JPEG 圖像品質的值。
            讀寫 **int**.


### 備註

僅在文件包含 JPEG 圖像時才會產生作用。


在保存為 PDF 格式時，使用此屬性取得或設定文件中圖像的品質。
            該值的範圍為 0 到 100，0 代表最差品質但壓縮率最高，100 代表最佳品質但壓縮率最低。


預設值為 **95** 。

### 定義:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### 參見
* 類別 [`IHtmlOptions`](/slides/python-net/zh-hant/aspose.slides.export/ihtmloptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)