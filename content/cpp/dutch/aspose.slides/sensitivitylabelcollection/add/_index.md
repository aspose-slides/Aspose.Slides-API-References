---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt het gevoeligheidslabel toe aan het einde van de collectie.
type: docs
weight: 27
url: /nl/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method


Voegt het gevoeligheidslabel toe aan het einde van de collectie.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Het id van het gevoeligheidslabel. |
| siteId | [System::Guid](../../../system/guid/) | De Azure Active Directory (Azure AD) site-identificatie. |
| isEnabled | **bool** | Vlag aangeeft of het gevoeligheidslabel is ingeschakeld. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | De toewijzingsmethode voor het gevoeligheidslabel. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method


Voegt een [SensitivityLabel](../../sensitivitylabel/) toe aan de collectie.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Het [SensitivityLabel](../../sensitivitylabel/)-object dat aan het einde van de collectie moet worden toegevoegd. |

### Retourwaarde

De index waarop de [SensitivityLabel](../../sensitivitylabel/) is toegevoegd.

## Zie ook

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISensitivityLabel](../../isensitivitylabel/)
* Klasse [String](../../../system/string/)
* Klasse [Guid](../../../system/guid/)
* Klasse [SensitivityLabelCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)