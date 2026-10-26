---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt das Sensitivitätslabel am Ende der Sammlung hinzu.
type: docs
weight: 27
url: /de/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method

Fügt das Sensitivitätslabel am Ende der Sammlung hinzu.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Die ID des Sensitivitätslabels. |
| siteId | [System::Guid](../../../system/guid/) | Der Azure Active Directory (Azure AD)-Site-Bezeichner. |
| isEnabled | **bool** | Flag gibt an, ob das Sensitivitätslabel aktiviert ist. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Die Zuweisungsmethode für das Sensitivitätslabel. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method

Fügt ein [SensitivityLabel](../../sensitivitylabel/) zur Sammlung hinzu.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Das [SensitivityLabel](../../sensitivitylabel/)-Objekt, das am Ende der Sammlung hinzugefügt werden soll. |

### Rückgabewert

Der Index, an dem das [SensitivityLabel](../../sensitivitylabel/) hinzugefügt wurde.

## Siehe auch

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISensitivityLabel](../../isensitivitylabel/)
* Klasse [String](../../../system/string/)
* Klasse [Guid](../../../system/guid/)
* Klasse [ISensitivityLabelCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)