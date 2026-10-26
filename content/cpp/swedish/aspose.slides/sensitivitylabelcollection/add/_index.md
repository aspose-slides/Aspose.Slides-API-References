---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till känslighetsetiketten i slutet av samlingen.
type: docs
weight: 27
url: /sv/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metod

Lägger till känslighetsetiketten i slutet av samlingen.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Id för känslighetsetiketten. |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) webbplatsidentifierare. |
| isEnabled | **bool** | Flagga som anger om känslighetsetiketten är aktiverad. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Tilldelningsmetod för känslighetsetiketten. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metod

Lägger till en [SensitivityLabel](../../sensitivitylabel/) i samlingen.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | [SensitivityLabel](../../sensitivitylabel/)-objektet som ska läggas till i slutet av samlingen. |

### Returvärde

Indexet där [SensitivityLabel](../../sensitivitylabel/) lades till.

## Se även

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [SensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)