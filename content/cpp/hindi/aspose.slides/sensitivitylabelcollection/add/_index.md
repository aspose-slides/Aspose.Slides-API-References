---
title: Add()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह के अंत में संवेदनशीलता लेबल जोड़ता है।
type: docs
weight: 27
url: /hi/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) मेथड

संग्रह के अंत में संवेदनशीलता लेबल जोड़ता है।

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | संवेदनशीलता लेबल की id। |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) साइट पहचानकर्ता। |
| isEnabled | **bool** | फ़्लैग दर्शाता है कि संवेदनशीलता लेबल सक्षम है। |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | संवेदनशीलता लेबल के लिए असाइनमेंट विधि। |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) मेथड

संग्रह में एक [SensitivityLabel](../../sensitivitylabel/) जोड़ता है।

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | संग्रह के अंत में जोड़े जाने वाले [SensitivityLabel](../../sensitivitylabel/) ऑब्जेक्ट। |

### रिटर्न वैल्यू

वह सूचकांक जिस पर [SensitivityLabel](../../sensitivitylabel/) जोड़ा गया था।

## देखें

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [SensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)