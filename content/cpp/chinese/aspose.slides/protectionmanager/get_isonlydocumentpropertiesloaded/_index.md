---
title: get_IsOnlyDocumentPropertiesLoaded()
second_title: Aspose.Slides for C++ API 参考
description: 如果演示文稿文件受密码保护且该文件的文档属性为公开，则此属性有意义。值为 true 表示仅在不使用密码的情况下从加密的演示文稿文件加载文档属性。值为 false 表示使用正确的密码加载整个加密的演示文稿，而不仅仅加载文档属性。如果演示文稿未加密，则属性值始终为 false。如果加密文件的文档属性不是公开的，则属性值始终为 false。如果 Presentation.EncryptDocumentProperties 为 true，则 IsOnlyDocumentPropertiesLoaded 属性值始终为 false。只读 bool.
type: docs
weight: 40
url: /zh/aspose.slides/protectionmanager/get_isonlydocumentpropertiesloaded/
---
## ProtectionManager::get_IsOnlyDocumentPropertiesLoaded() 方法

该属性在演示文稿文件受密码保护且该文件的文档属性为公开时有意义。值为 true 表示仅从加密的演示文稿文件加载文档属性而不使用密码。值为 false 表示使用正确的密码加载整个加密的演示文稿，而不仅仅加载文档属性。如果演示文稿未加密，则属性值始终为 false。如果加密文件的文档属性不是公开的，则属性值始终为 false。如果 Presentation.EncryptDocumentProperties 为 true，则 IsOnlyDocumentPropertiesLoaded 属性值始终为 false。只读 **bool**。

```cpp
bool Aspose::Slides::ProtectionManager::get_IsOnlyDocumentPropertiesLoaded() override
```

## 参见

* 类 [ProtectionManager](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)