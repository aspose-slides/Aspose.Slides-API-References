---
title: add method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
Fügt ein SensitivityLabel zur Sammlung hinzu.

### Rückgabewert
Der Index, an dem das SensitivityLabel hinzugefügt wurde.

```python
def add(self, label):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/de/aspose.slides/isensitivitylabel) | Das SensitivityLabel-Objekt, das am Ende der Sammlung hinzugefügt werden soll. |

### Ausnahmen
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wird ausgelöst, wenn das SensitivityLabel mit derselben Id bereits hinzugefügt wurde. |

## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}

```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/de/aspose.slides/sensitivitylabelassignmenttype) |  |

### Siehe auch
* Klasse [`ISensitivityLabel`](/slides/python-net/de/aspose.slides/isensitivitylabel)
* Aufzählung [`SensitivityLabelAssignmentType`](/slides/python-net/de/aspose.slides/sensitivitylabelassignmenttype)
* Klasse [`SensitivityLabelCollection`](/slides/python-net/de/aspose.slides/sensitivitylabelcollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)