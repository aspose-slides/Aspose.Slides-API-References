---
title: set_OnlyLoadDocumentProperties()
second_title: Aspose.Slides for C++ API 参考
description: 该属性在演示文稿文件受密码保护时才有意义。true 表示只能从加密的演示文稿文件中加载文档属性，并且应忽略密码。false 表示必须使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并会抛出异常。写入 bool。
type: docs
weight: 144
url: /zh/aspose.slides/loadoptions/set_onlyloaddocumentproperties/
---
## LoadOptions::set_OnlyLoadDocumentProperties(bool) 方法


如果演示文稿文件受密码保护，则此属性有意义。true 表示只能从加密的演示文稿文件中加载文档属性，并且应忽略密码。false 表示必须使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性并会抛出异常。写入 **bool**。

```cpp
void Aspose::Slides::LoadOptions::set_OnlyLoadDocumentProperties(bool value) override
```

## 另见

* 类 [LoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)