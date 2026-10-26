---
title: Add()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: संग्रह के अंत में संवेदनशीलता लेबल जोड़ता है।
type: docs
weight: 27
url: /hi/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) विधि

संग्रह के अंत में संवेदनशीलता लेबल जोड़ता है।

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | संवेदनशीलता लेबल का आईडी। |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) साइट पहचानकर्ता। |
| isEnabled | **bool** | फ़्लैग दर्शाता है कि संवेदनशीलता लेबल सक्रिय है या नहीं। |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | संवेदनशीलता लेबल के लिए असाइनमेंट विधि। |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) विधि

संग्रह में एक [SensitivityLabel](../../sensitivitylabel/) जोड़ता है।

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | संग्रह के अंत में जोड़े जाने वाले [SensitivityLabel](../../sensitivitylabel/) ऑब्जेक्ट। |

### वापसी मान

जिस सूचकांक पर [SensitivityLabel](../../sensitivitylabel/) जोड़ा गया था।

## सम्बंधित देखें

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [ISensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)