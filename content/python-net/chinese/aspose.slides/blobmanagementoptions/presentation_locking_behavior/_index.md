---
title: presentation_locking_behavior property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/blobmanagementoptions/presentation_locking_behavior/
weight: 40
---
## presentation_locking_behavior 属性
此属性定义 Presentation 类的实例在其生命周期内是否可以成为源 - 文件 
            或流在实例生命周期内。如果实例是所有者，它会锁定源。这有助于在处理 BLOB 时提升内存消耗和性能，但源（流或文件） 
            在 Presentation 实例的生命周期内无法更改。

### 定义:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```


### 另请参见
* 类 [`BlobManagementOptions`](/slides/python-net/zh/aspose.slides/blobmanagementoptions)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)