---
title: save_metafiles_as_png property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png 屬性
True 代表將簡報中使用的所有 metafiles 轉換為 PNG 圖像。
            讀寫 **bool**.

### 備註

預設為 **true** 。
            Pdf 文件可以包含向量圖形和點陣圖像。 
            如果 SaveMetafilesAsPng 設為 true，則來源 Metafile 
            圖像會被轉換為 Png 格式，並以點陣圖的方式儲存至 Pdf。 
            如果 SaveMetafilesAsPng 設為 false，則來源 Metafile 
            會被轉換為 Pdf 向量圖形。 
            每種方式各有優缺點。 
            例如，若 Metafile 轉換為 PNG，則在隨後的文件縮放過程中可能會出現品質損失。 
            若 Metafile 轉換為 Pdf 向量圖形，則可能會在 Pdf 檢視工具中產生效能問題。

### 定義:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### 另請參閱
* 類別 [`PdfOptions`](/slides/python-net/zh-hant/aspose.slides.export/pdfoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)