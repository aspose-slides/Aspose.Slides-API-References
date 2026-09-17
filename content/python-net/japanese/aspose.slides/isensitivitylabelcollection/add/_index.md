---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
コレクションに SensitivityLabel を追加します。

### 戻り値

SensitivityLabel が追加されたインデックス。

```python
def add(self, label):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/ja/aspose.slides/isensitivitylabel) | コレクションの末尾に追加する SensitivityLabel オブジェクト。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 同じ Id を持つ感度ラベルが既に追加されている場合にスローされます。 |

## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}

```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/ja/aspose.slides/sensitivitylabelassignmenttype) |  |

### 参照
* クラス [`ISensitivityLabel`](/slides/python-net/ja/aspose.slides/isensitivitylabel)
* クラス [`ISensitivityLabelCollection`](/slides/python-net/ja/aspose.slides/isensitivitylabelcollection)
* 列挙型 [`SensitivityLabelAssignmentType`](/slides/python-net/ja/aspose.slides/sensitivitylabelassignmenttype)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)