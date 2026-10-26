---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
コレクションに SensitivityLabel を追加します。

### 戻り値

SensitivityLabel が追加されたインデックスを返します。

```python
def add(self, label):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/ja/aspose.slides/isensitivitylabel) | コレクションの末尾に追加する SensitivityLabel オブジェクト。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 同じ Id を持つ SensitivityLabel がすでに追加されている場合にスローされます。 |

## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}

```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/ja/aspose.slides/sensitivitylabelassignmenttype) |  |

### 参照
* クラス [`ISensitivityLabel`](/slides/python-net/ja/aspose.slides/isensitivitylabel)
* 列挙体 [`SensitivityLabelAssignmentType`](/slides/python-net/ja/aspose.slides/sensitivitylabelassignmenttype)
* クラス [`SensitivityLabelCollection`](/slides/python-net/ja/aspose.slides/sensitivitylabelcollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)