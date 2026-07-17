---
title: set_OnlyLoadDocumentProperties()
second_title: Aspose.Slides C++ API 参考
description: 此属性在演示文稿文件受密码保护时有意义。true 表示只能从加密的演示文稿文件中加载文档属性，并且忽略密码。false 表示必须使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并将抛出异常。写入 **bool**。
type: docs
weight: 144
url: /zh/aspose.slides/iloadoptions/set_onlyloaddocumentproperties/
---
## ILoadOptions::set_OnlyLoadDocumentProperties(bool) 方法

此属性在演示文稿文件受密码保护时有意义。true 表示只能从加密的演示文稿文件中加载文档属性，且忽略密码。false 表示必须使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并会抛出异常。写入 **bool**。

```cpp
virtual void Aspose::Slides::ILoadOptions::set_OnlyLoadDocumentProperties(bool value)=0
```

## 另请参阅

* 类 [ILoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)