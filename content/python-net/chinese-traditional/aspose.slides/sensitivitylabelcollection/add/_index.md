---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
將 SensitivityLabel 新增至集合中。

### 返回值

新增 SensitivityLabel 的索引位置。

```python
def add(self, label):
    ...
```

| 參數 | 型別 | 說明 |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/zh-hant/aspose.slides/isensitivitylabel) | 位於集合末端的 SensitivityLabel 物件 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當已經加入具有相同 Id 的敏感性標籤時拋出此例外。 |

## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}

```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```

| 參數 | 型別 | 說明 |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/zh-hant/aspose.slides/sensitivitylabelassignmenttype) |  |

### 參見
* 類別 [`ISensitivityLabel`](/slides/python-net/zh-hant/aspose.slides/isensitivitylabel)
* 列舉 [`SensitivityLabelAssignmentType`](/slides/python-net/zh-hant/aspose.slides/sensitivitylabelassignmenttype)
* 類別 [`SensitivityLabelCollection`](/slides/python-net/zh-hant/aspose.slides/sensitivitylabelcollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)