---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/loadoptions/delete_embedded_binary_objects/
weight: 70
---
## delete_embedded_binary_objects 屬性
確定 Aspose.Slides 在載入簡報時是否會刪除所有嵌入的二進位物件。

嵌入的二進位物件類型：

* VBA 專案 [`IPresentation.vba_project`](/slides/python-net/zh-hant/aspose.slides/ipresentation/vba_project)
* OLE 物件嵌入資料 [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX 控制項二進位資料 [`IControl.active_x_control_binary`](/slides/python-net/zh-hant/aspose.slides/icontrol/active_x_control_binary)

讀寫 **bool**。

### 備註

預設為 **false** 。

### 定義:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### 另請參閱
* 類別 [`LoadOptions`](/slides/python-net/zh-hant/aspose.slides/loadoptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)