---
title: jpeg_quality property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.export/ipdfoptions/jpeg_quality/
weight: 150
---
## jpeg_quality 屬性
取得或設定決定 PDF 文件內 JPEG 影像品質的值。
            讀寫 **int**.


### 備註

僅在文件包含 JPEG 影像時才會產生效果。


使用此屬性在儲存為 PDF 格式時取得或設定文件內影像的品質。
            值可以在 0 到 100 之間變化，其中 0 表示最低品質但最高壓縮，100 表示最高品質但最低壓縮。


預設值為 **100** .

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
* 類別 [`IPdfOptions`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)