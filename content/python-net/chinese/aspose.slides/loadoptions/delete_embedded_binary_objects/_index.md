---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/loadoptions/delete_embedded_binary_objects/
weight: 70
---
## delete_embedded_binary_objects 属性
确定在加载演示文稿时 Aspose.Slides 是否会删除所有嵌入的二进制对象。

嵌入二进制对象的类型：

* VBA 项目 [`IPresentation.vba_project`](/slides/python-net/zh/aspose.slides/ipresentation/vba_project)
* OLE 对象嵌入数据 [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX 控件二进制数据 [`IControl.active_x_control_binary`](/slides/python-net/zh/aspose.slides/icontrol/active_x_control_binary)

读/写 **bool**。

### 备注

默认是 **false** 。

### 定义：
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### 另请参见
* 类 [`LoadOptions`](/slides/python-net/zh/aspose.slides/loadoptions)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)