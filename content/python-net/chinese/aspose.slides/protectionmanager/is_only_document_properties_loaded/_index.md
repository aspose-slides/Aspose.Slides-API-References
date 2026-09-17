---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded 属性
此属性在演示文稿文件受密码保护且该文件的文档 
            属性为公开时才有意义。
            值为 true 表示仅从加密的演示文稿文件中加载文档属性，而不使用密码。
            值为 false 表示使用正确的密码加载整个加密的演示文稿，而不仅加载文档属性。
            如果演示文稿未加密，则属性值始终为 false。
            如果加密文件的文档属性不是公开的，则属性值始终为 false。
            如果 Presentation.EncryptDocumentProperties 为 true，则 IsOnlyDocumentPropertiesLoaded 
            属性值始终为 false。
            只读 **bool**。

### 定义:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```


### 另见
* 类 [`ProtectionManager`](/slides/python-net/zh/aspose.slides/protectionmanager)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)