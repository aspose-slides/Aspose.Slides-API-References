---
title: only_load_document_properties property
second_title: Aspose.Slides for Python via .NET API 参考
description:
type: docs
url: /zh/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties 属性
如果演示文稿文件受密码保护，此属性才有意义。
            值为 true 表示只能从加密的
            演示文稿文件中加载文档属性并忽略密码。
            值为 false 表示必须使用正确的
            密码加载整个加密的演示文稿。
            如果演示文稿未加密，则属性值始终被忽略。
            如果加密文件的文档属性不是公共的且属性值为 true，则
            文档属性无法加载，将抛出异常。
            读写 **bool**。

### 定义：
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### 另见
* 类 [`ILoadOptions`](/slides/python-net/zh/aspose.slides/iloadoptions)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)