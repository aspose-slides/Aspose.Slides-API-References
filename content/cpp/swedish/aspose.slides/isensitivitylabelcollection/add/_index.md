---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till känslighetsetiketten i slutet av samlingen.
type: docs
weight: 27
url: /sv/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metod

Lägger till känslighetsetiketten i slutet av samlingen.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Id för känslighetsetiketten. |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) webbplatsidentifierare. |
| isEnabled | **bool** | Flagga som indikerar om känslighetsetiketten är aktiverad. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Tilldelningsmetod för känslighetsetiketten. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metod

Lägger till en [SensitivityLabel](../../sensitivitylabel/) i samlingen.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Objektet [SensitivityLabel](../../sensitivitylabel/) som ska läggas till i slutet av samlingen. |

### Returvärde

Indexet där [SensitivityLabel](../../sensitivitylabel/) lades till.

## Se även

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISensitivityLabel](../../isensitivitylabel/)
* Klass [String](../../../system/string/)
* Klass [Guid](../../../system/guid/)
* Klass [ISensitivityLabelCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)