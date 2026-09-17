---
title: add method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
将 SensitivityLabel 添加到集合中。

### 返回值

SensitivityLabel 被添加的位置索引。

```python
def add(self, label):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/zh/aspose.slides/isensitivitylabel) | 要添加到集合末尾的 SensitivityLabel 对象。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当具有相同 Id 的敏感度标签已被添加时抛出。 |

## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}

```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/zh/aspose.slides/sensitivitylabelassignmenttype) |  |

### 另请参见
* 类 [`ISensitivityLabel`](/slides/python-net/zh/aspose.slides/isensitivitylabel)
* 类 [`ISensitivityLabelCollection`](/slides/python-net/zh/aspose.slides/isensitivitylabelcollection)
* 枚举 [`SensitivityLabelAssignmentType`](/slides/python-net/zh/aspose.slides/sensitivitylabelassignmenttype)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)