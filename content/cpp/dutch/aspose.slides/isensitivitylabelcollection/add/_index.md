---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt het gevoeligheidslabel toe aan het einde van de collectie.
type: docs
weight: 27
url: /nl/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) methode

Voegt het gevoeligheidslabel toe aan het einde van de collectie.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | De id van het gevoeligheidslabel. |
| siteId | [System::Guid](../../../system/guid/) | De Azure Active Directory (Azure AD) site-identificatie. |
| isEnabled | **bool** | Vlag geeft aan of het gevoeligheidslabel is ingeschakeld. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | De toewijzingsmethode voor het gevoeligheidslabel. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) methode

Voegt een [SensitivityLabel](../../sensitivitylabel/) toe aan de collectie.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
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
* Klasse [ISensitivityLabelCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)