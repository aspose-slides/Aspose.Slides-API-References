---
title: PresentationInfo class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/presentationinfo/
---
## PresentationInfo 类

有关演示文稿文件的信息

PresentationInfo 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`is_encrypted`](/slides/python-net/zh/aspose.slides/presentationinfo/is_encrypted/) | 如果绑定的演示文稿已加密，则返回 True，否则返回 False。<br/>            只读 **bool**. |
| [`is_password_protected`](/slides/python-net/zh/aspose.slides/presentationinfo/is_password_protected/) | 获取一个值，指示绑定的演示文稿是否受到打开密码的保护。 |
| [`is_write_protected`](/slides/python-net/zh/aspose.slides/presentationinfo/is_write_protected/) | 获取一个值，指示绑定的演示文稿是否受到写入保护。 |
| [`load_format`](/slides/python-net/zh/aspose.slides/presentationinfo/load_format/) | 获取绑定的演示文稿的格式。<br/>            只读 [`LoadFormat`](/slides/python-net/zh/aspose.slides/loadformat). |

## 方法

| Method | Description |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/zh/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | 将绑定的演示文稿写入流。 |
| [`write_binded_presentation(self, file)`](/slides/python-net/zh/aspose.slides/presentationinfo/write_binded_presentation/#str) | 将绑定的演示文稿写入文件。 |
| [`check_password(self, password)`](/slides/python-net/zh/aspose.slides/presentationinfo/check_password/#str) | 检查针对受打开密码保护的演示文稿的密码是否正确。 |
| [`check_write_protection(self, password)`](/slides/python-net/zh/aspose.slides/presentationinfo/check_write_protection/#str) | 检查针对受写入保护的演示文稿的修改密码是否正确。 |
| [`read_document_properties(self)`](/slides/python-net/zh/aspose.slides/presentationinfo/read_document_properties/#) | 获取绑定的演示文稿的文档属性。 |
| [`update_document_properties(self, document_properties)`](/slides/python-net/zh/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | 更新绑定的演示文稿的属性。 |


### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)