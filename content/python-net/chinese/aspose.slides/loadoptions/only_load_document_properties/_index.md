---
title: only_load_document_properties property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties 属性
如果演示文稿文件受密码保护，则此属性有意义。
            如果值为 true，则表示必须仅从加密的演示文稿文件加载文档属性，并且必须忽略密码。
            如果值为 false，则表示必须使用正确的密码加载整个加密的演示文稿。
            如果演示文稿未加密，则属性值始终被忽略。
            如果加密文件的文档属性不是公开的且属性值为 true，则无法加载文档属性，并将抛出异常。
            读/写 **bool**。

### 定义:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### 另见
* 类 [`LoadOptions`](/slides/python-net/zh/aspose.slides/loadoptions)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)