---
title: add method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/isensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
SensitivityLabel को संग्रह में जोड़ता है।

### Returns
जिस इंडेक्स पर SensitivityLabel जोड़ा गया, वह लौटाता है।

```python
def add(self, label):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/hi/aspose.slides/isensitivitylabel) | संग्रह के अंत में जोड़े जाने वाले SensitivityLabel ऑब्जेक्ट। |

### Exceptions
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब समान Id वाला संवेदनशीलता लेबल पहले ही जोड़ दिया गया हो, तब फेंका जाता है। |

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
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/hi/aspose.slides/sensitivitylabelassignmenttype) |  |

### See Also
* class [`ISensitivityLabel`](/slides/python-net/hi/aspose.slides/isensitivitylabel)
* class [`ISensitivityLabelCollection`](/slides/python-net/hi/aspose.slides/isensitivitylabelcollection)
* enumeration [`SensitivityLabelAssignmentType`](/slides/python-net/hi/aspose.slides/sensitivitylabelassignmenttype)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)