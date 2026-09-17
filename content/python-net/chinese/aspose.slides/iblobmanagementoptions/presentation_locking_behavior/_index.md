---
title: presentation_locking_behavior property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior 属性
此属性定义 Presentation 类的实例在其生命周期内是否可以成为源（文件或流）的所有者。如果实例是所有者，它会锁定源。这有助于在处理 BLOB 时改进内存消耗和性能，但在 Presentation 实例的生命周期内，源（流或文件）不能被更改。这是一个示例：

### 定义：
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```


### 另见
* 类 [`IBlobManagementOptions`](/slides/python-net/zh/aspose.slides/iblobmanagementoptions)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)