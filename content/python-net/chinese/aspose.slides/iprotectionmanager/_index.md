---
title: IProtectionManager class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iprotectionmanager/
---
## IProtectionManager 类

演示文稿密码保护管理。

IProtectionManager 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/zh/aspose.slides/iprotectionmanager/encrypt_document_properties/) | 如果演示文稿受密码保护，此属性才有意义。<br/>            如果为 true，则文档属性在演示文稿文件中加密。<br/>            如果为 false，则文档属性是公开的，而演示文稿已加密。<br/>            读写 **bool**。 |
| [`is_encrypted`](/slides/python-net/zh/aspose.slides/iprotectionmanager/is_encrypted/) | 获取一个值，指示此实例是否已加密。<br/>            只读 **bool**。 |
| [`is_only_document_properties_loaded`](/slides/python-net/zh/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | 如果演示文稿文件受密码保护且该文件的文档属性是公开的，此属性才有意义。<br/>            为 true 时表示仅从加密的演示文稿文件中加载文档属性，而不使用密码。<br/>            为 false 时表示使用正确的密码加载整个加密的演示文稿，而不仅仅加载文档属性。<br/>            如果演示文稿未加密，则属性值始终为 false。<br/>            如果加密文件的文档属性不是公开的，则属性值始终为 false。<br/>            如果 PresentationEx.EncryptDocumentProperties 为 true，则 IsOnlyDocumentPropertiesLoaded <br/>            属性值始终为 false。<br/>            只读 **bool**。 |
| [`is_write_protected`](/slides/python-net/zh/aspose.slides/iprotectionmanager/is_write_protected/) | 获取一个值，指示此演示文稿是否受写保护。<br/>            只读 **bool**。 |
| [`encryption_password`](/slides/python-net/zh/aspose.slides/iprotectionmanager/encryption_password/) | 返回加密密码。<br/>            只读 **str**。 |
| [`read_only_recommended`](/slides/python-net/zh/aspose.slides/iprotectionmanager/read_only_recommended/) | 获取或设置只读建议。<br/>            读写 **bool**。 |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/zh/aspose.slides/iprotectionmanager/encrypt/#str) | 使用指定密码加密演示文稿。 |
| [`remove_encryption(self)`](/slides/python-net/zh/aspose.slides/iprotectionmanager/remove_encryption/#) | 移除加密。 |
| [`set_write_protection(self, password)`](/slides/python-net/zh/aspose.slides/iprotectionmanager/set_write_protection/#str) | 使用指定密码为此演示文稿设置写保护。 |
| [`remove_write_protection(self)`](/slides/python-net/zh/aspose.slides/iprotectionmanager/remove_write_protection/#) | 移除此演示文稿的写保护。 |
| [`check_write_protection(self, password)`](/slides/python-net/zh/aspose.slides/iprotectionmanager/check_write_protection/#str) | 确定演示文稿是否已受密码保护以进行修改。 |

### 另请参阅
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)