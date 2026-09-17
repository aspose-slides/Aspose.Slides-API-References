---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded 属性
如果演示文稿文件受密码保护且该文件的文档属性是公开的，则此属性有意义。
true 值表示仅在不使用密码的情况下从加密的演示文稿文件加载文档属性。
false 值表示使用正确的密码加载整个加密的演示文稿，而不仅仅加载文档属性。
如果演示文稿未加密，则属性值始终为 false。
如果加密文件的文档属性不是公开的，则属性值始终为 false。
如果 PresentationEx.EncryptDocumentProperties 为 true，则 IsOnlyDocumentPropertiesLoaded 属性的值始终为 false。
只读 **bool**。

### 定义:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### 另请参见
* 类 [`IProtectionManager`](/slides/python-net/zh/aspose.slides/iprotectionmanager)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)