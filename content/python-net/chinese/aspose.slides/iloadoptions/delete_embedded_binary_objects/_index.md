---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects 属性
确定在加载演示文稿时 Aspose.Slides 是否会删除所有嵌入的二进制对象。
            
嵌入的二进制对象的类型：


* VBA Project [`IPresentation.vba_project`](/slides/python-net/zh/aspose.slides/ipresentation/vba_project)
* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/zh/aspose.slides/icontrol/active_x_control_binary)


            读/写 **bool**.


### 备注

默认是 **false** .

### 定义:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```


### 另请参见
* class [`ILoadOptions`](/slides/python-net/zh/aspose.slides/iloadoptions)
* module [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)