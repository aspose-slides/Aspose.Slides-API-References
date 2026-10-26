---
title: IPresentationInfo class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ipresentationinfo/
---
## IPresentationInfo 类

有关演示文件的信息

IPresentationInfo 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`is_encrypted`](/slides/python-net/zh/aspose.slides/ipresentationinfo/is_encrypted/) | 如果绑定的演示文稿已加密则返回 True，否则返回 False。<br/>            只读 **bool**. |
| [`is_password_protected`](/slides/python-net/zh/aspose.slides/ipresentationinfo/is_password_protected/) | 获取一个值，指示绑定的演示文稿是否受打开密码保护。 |
| [`is_write_protected`](/slides/python-net/zh/aspose.slides/ipresentationinfo/is_write_protected/) | 获取一个值，指示绑定的演示文稿是否受写入保护。 |
| [`load_format`](/slides/python-net/zh/aspose.slides/ipresentationinfo/load_format/) | 获取绑定的演示文稿的格式。<br/>            只读 [`LoadFormat`](/slides/python-net/zh/aspose.slides/loadformat). |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/zh/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | 将绑定的演示文稿写入流。 |
| [`write_binded_presentation(self, file)`](/slides/python-net/zh/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | 将绑定的演示文稿写入文件。 |
| [`check_password(self, password)`](/slides/python-net/zh/aspose.slides/ipresentationinfo/check_password/#str) | 检查受打开密码保护的演示文稿的密码是否正确。 |
| [`check_write_protection(self, password)`](/slides/python-net/zh/aspose.slides/ipresentationinfo/check_write_protection/#str) | 检查受写保护的演示文稿的修改密码是否正确。 |
| [`read_document_properties(self)`](/slides/python-net/zh/aspose.slides/ipresentationinfo/read_document_properties/#) | 获取绑定的演示文稿的文档属性。 |
| [`update_document_properties(self, document_properties)`](/slides/python-net/zh/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | 更新绑定的演示文稿的属性。 |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)