---
title: Control class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/control/
---
## Control 类

表示一个 ActiveX 控件。

此 Control 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`persistence`](/slides/python-net/zh/aspose.slides/control/persistence/) | 获取用于存储 ActiveX 控件属性的方法。<br/>            只读 [`PersistenceType`](/slides/python-net/zh/aspose.slides/persistencetype)。 |
| [`name`](/slides/python-net/zh/aspose.slides/control/name/) | 获取或设置此控件的名称。<br/>            读写 **str**。 |
| [`class_id`](/slides/python-net/zh/aspose.slides/control/class_id/) | 获取此控件的类标识符。<br/>            只读 **System.Guid**。 |
| [`substitute_picture_format`](/slides/python-net/zh/aspose.slides/control/substitute_picture_format/) | 返回 Control 图像填充属性对象。<br/>            只读 [`IPictureFillFormat`](/slides/python-net/zh/aspose.slides/ipicturefillformat)。 |
| [`frame`](/slides/python-net/zh/aspose.slides/control/frame/) | 获取或设置控件的框架。<br/>            读写 [`IShapeFrame`](/slides/python-net/zh/aspose.slides/ishapeframe)。 |
| [`properties`](/slides/python-net/zh/aspose.slides/control/properties/) | 返回 ActiveX 属性的集合。<br/>            注意：Aspose.Slides 仅支持基于 XML 的 ActiveX 属性。如果属性以二进制格式存储，此属性将返回 None。<br/>            只读 [`IControlPropertiesCollection`](/slides/python-net/zh/aspose.slides/icontrolpropertiescollection)。 |
| [`active_x_control_binary`](/slides/python-net/zh/aspose.slides/control/active_x_control_binary/) | 指定在持久化方法为 PersistStream、PersistStreamInit 或 PersistStorage 时，ActiveX 控件的持久性。 |
| [`slide`](/slides/python-net/zh/aspose.slides/control/slide/) |  |
| [`presentation`](/slides/python-net/zh/aspose.slides/control/presentation/) |  |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)