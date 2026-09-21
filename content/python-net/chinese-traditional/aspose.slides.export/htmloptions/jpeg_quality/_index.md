---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/htmloptions/jpeg_quality/
weight: 90
---
## jpeg_quality 屬性
取得或設定 PDF 文件中 JPEG 影像品質的值。
            讀寫 **int**.


### 備註

只有文件包含 JPEG 影像時才會產生作用。


在將文件保存為 PDF 格式時，使用此屬性取得或設定文件內影像的品質。
            此值的範圍為 0 到 100，其中 0 表示最差品質但最高壓縮，100 表示最佳品質但最低壓縮。


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


### 另請參閱
* 類別 [`HtmlOptions`](/slides/python-net/zh-hant/aspose.slides.export/htmloptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)