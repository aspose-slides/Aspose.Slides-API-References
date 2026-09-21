---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
將 SensitivityLabel 新增至集合。

### 返回
新增 SensitivityLabel 的索引位置。

```python
def add(self, label):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/zh-hant/aspose.slides/isensitivitylabel) | 要在集合末端新增的 SensitivityLabel 物件。 |

### 例外
| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 當已經新增具有相同 Id 的敏感度標籤時拋出此例外。 |

## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}

```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/zh-hant/aspose.slides/sensitivitylabelassignmenttype) |  |

### 另請參閱
* 類別 [`ISensitivityLabel`](/slides/python-net/zh-hant/aspose.slides/isensitivitylabel)
* 類別 [`ISensitivityLabelCollection`](/slides/python-net/zh-hant/aspose.slides/isensitivitylabelcollection)
* 列舉 [`SensitivityLabelAssignmentType`](/slides/python-net/zh-hant/aspose.slides/sensitivitylabelassignmenttype)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)