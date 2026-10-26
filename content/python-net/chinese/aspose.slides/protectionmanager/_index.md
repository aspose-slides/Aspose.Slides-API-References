---
title: ProtectionManager class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/protectionmanager/
---
## ProtectionManager 类

演示文稿密码保护管理。

ProtectionManager 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/zh/aspose.slides/protectionmanager/encrypt_document_properties/) | 如果演示文稿受密码保护，此属性才有意义。<br/> 如果 true 则文档属性在演示文件中被加密。<br/> 如果 false，则在演示已加密的情况下，文档属性是公开的。<br/> 读/写 **bool**. |
| [`is_encrypted`](/slides/python-net/zh/aspose.slides/protectionmanager/is_encrypted/) | 获取一个值，指示此实例是否已加密。<br/> 只读 **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/zh/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | 如果演示文件受密码保护且该文件的文档属性是公开的，则此属性才有意义。<br/> 值为 true 表示仅从加密的演示文件中加载文档属性，而不使用密码。<br/> 值为 false 表示使用正确的密码加载整个加密的演示文件，而不仅仅加载文档属性。<br/> 如果演示未加密，则属性值始终为 false。<br/> 如果加密文件的文档属性不是公开的，则属性值始终为 false。<br/> 如果 Presentation.EncryptDocumentProperties 为 true，则 IsOnlyDocumentPropertiesLoaded 属性值始终为 false。<br/> 只读 **bool**. |
| [`is_write_protected`](/slides/python-net/zh/aspose.slides/protectionmanager/is_write_protected/) | 获取一个值，指示此演示文稿是否受到写保护。<br/> 只读 **bool**. |
| [`encryption_password`](/slides/python-net/zh/aspose.slides/protectionmanager/encryption_password/) | 获取用于演示加密的密码。<br/> 只读 **str**. |
| [`read_only_recommended`](/slides/python-net/zh/aspose.slides/protectionmanager/read_only_recommended/) | 获取或设置只读建议。<br/> 读/写 **bool**. |

## 方法

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/zh/aspose.slides/protectionmanager/encrypt/#str) | 使用指定的密码加密演示文稿。 |
| [`remove_encryption(self)`](/slides/python-net/zh/aspose.slides/protectionmanager/remove_encryption/#) | 移除加密。 |
| [`set_write_protection(self, password)`](/slides/python-net/zh/aspose.slides/protectionmanager/set_write_protection/#str) | 使用指定的密码为此演示文稿设置写保护。 |
| [`remove_write_protection(self)`](/slides/python-net/zh/aspose.slides/protectionmanager/remove_write_protection/#) | 移除此演示文稿的写保护。 |
| [`check_write_protection(self, password)`](/slides/python-net/zh/aspose.slides/protectionmanager/check_write_protection/#str) | 确定演示文稿是否受密码保护，以便进行修改。 |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)