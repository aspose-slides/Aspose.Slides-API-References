---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects 屬性
判斷 Aspose.Slides 在載入簡報時是否會刪除所有嵌入的二進位物件。

嵌入的二進位物件類型：

* VBA Project [`IPresentation.vba_project`](/slides/python-net/zh-hant/aspose.slides/ipresentation/vba_project)
* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/zh-hant/aspose.slides/icontrol/active_x_control_binary)

            讀/寫 **bool**。

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
* 類別 [`ILoadOptions`](/slides/python-net/zh-hant/aspose.slides/iloadoptions)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)