---
title: save_metafiles_as_png property
second_title: Aspose.Slides for Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png 屬性
True to convert all metafiles used in a presentation to the PNG images.
            Read/write **bool**.

### 備註
Default is **true** .
            Pdf 文件可以包含向量圖形和點陣圖像。 
            If SaveMetafilesAsPng is set to true then source Metafile 
            圖像會被轉換為 Png 格式，並儲存為 Pdf 的點陣 
            圖像。 If SaveMetafilesAsPng is set to false then source Metafile 
            會被轉換為 Pdf 向量圖形。 Each approach has advantages 
            and disadvantages. For example, if Metafile is converted to PNG, 
            then some quality loss is possible during resulting 
            document scaling. If Metafile is converted to Pdf vector graphics, 
            then performance issues in Pdf viewing tool are possible.

### 定義：
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### 另見
* 類別 [`IPdfOptions`](/slides/python-net/zh-hant/aspose.slides.export/ipdfoptions)
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)