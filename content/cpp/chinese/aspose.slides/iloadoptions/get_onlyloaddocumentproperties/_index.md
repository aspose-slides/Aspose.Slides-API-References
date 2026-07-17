---
title: get_OnlyLoadDocumentProperties()
second_title: Aspose.Slides for C++ API 参考
description: 该属性在演示文稿文件受密码保护时才有意义。true 表示只能从加密的演示文稿文件中加载文档属性，并且应忽略密码。false 表示必须使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性，并会抛出异常。读取 bool。
type: docs
weight: 131
url: /zh/aspose.slides/iloadoptions/get_onlyloaddocumentproperties/
---
## ILoadOptions::get_OnlyLoadDocumentProperties() 方法

如果演示文稿文件受密码保护，则此属性有意义。值为 true 表示只能从加密的演示文稿文件中加载文档属性，并且应忽略密码。值为 false 表示必须使用正确的密码加载整个加密的演示文稿。如果演示文稿未加密，则始终忽略属性值。如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性，并将抛出异常。读取 **bool**。

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_OnlyLoadDocumentProperties()=0
```

## 另请参见

* 类 [ILoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)