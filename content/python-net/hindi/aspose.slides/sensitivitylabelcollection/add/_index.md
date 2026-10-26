---
title: add method
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/sensitivitylabelcollection/add/
weight: 10
---
## add(self, label) {#isensitivitylabel}
एक SensitivityLabel को संग्रह में जोड़ता है।

### रिटर्न

इण्डेक्स जहाँ SensitivityLabel जोड़ा गया था.



```python
def add(self, label):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| label | [`ISensitivityLabel`](/slides/python-net/hi/aspose.slides/isensitivitylabel) | संग्रह के अंत में जोड़ने के लिए SensitivityLabel ऑब्जेक्ट। |

### अपवाद

| अपवाद | विवरण |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | जब समान Id वाला संवेदनशीलता लेबल पहले ही जोड़ लिया गया हो तो यह फेंका जाता है। |


## add(self, id, site_id, is_enabled, method_type) {#str-guid-bool-sensitivitylabelassignmenttype}



```python
def add(self, id, site_id, is_enabled, method_type):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| id | **str** |  |
| site_id | **Guid** |  |
| is_enabled | **bool** |  |
| method_type | [`SensitivityLabelAssignmentType`](/slides/python-net/hi/aspose.slides/sensitivitylabelassignmenttype) |  |



### संदर्भ
* क्लास [`ISensitivityLabel`](/slides/python-net/hi/aspose.slides/isensitivitylabel)
* एन्यूमरेशन [`SensitivityLabelAssignmentType`](/slides/python-net/hi/aspose.slides/sensitivitylabelassignmenttype)
* क्लास [`SensitivityLabelCollection`](/slides/python-net/hi/aspose.slides/sensitivitylabelcollection)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)