---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/pdfoptions/jpeg_quality/
weight: 160
---
## jpeg_quality 屬性
傳回或設定決定 PDF 文件中 JPEG 圖片品質的值。
            讀寫 **int**。


### 備註

僅在文件包含 JPEG 圖片時才有作用。


使用此屬性在以 PDF 格式儲存時取得或設定文件中圖像的品質。
            此值範圍為 0 到 100，0 代表最低品質但最高壓縮，100 代表最高品質但最低壓縮。


預設值為 **100** 。

### 定義:
```python
@property
def jpeg_quality(self):
    ...

@jpeg_quality.setter
def jpeg_quality(self, value):
    ...
```


### 另請參閱
* 類別 [`PdfOptions`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)