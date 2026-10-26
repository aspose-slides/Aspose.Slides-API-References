---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt das Sensitivitätslabel am Ende der Sammlung hinzu.
type: docs
weight: 27
url: /de/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) Methode


Fügt das Sensitivitätslabel am Ende der Sammlung hinzu.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Die ID des Sensitivitätslabels. |
| siteId | [System::Guid](../../../system/guid/) | Der Azure Active Directory (Azure AD) Site-Bezeichner. |
| isEnabled | **bool** | Flag gibt an, ob das Sensitivitätslabel aktiviert ist. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Die Zuweisungsmethode für das Sensitivitätslabel. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) Methode


Fügt ein [SensitivityLabel](../../sensitivitylabel/) zur Sammlung hinzu.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Das [SensitivityLabel](../../sensitivitylabel/)-Objekt, das am Ende der Sammlung hinzugefügt wird. |

### Rückgabewert

Der Index, an dem [SensitivityLabel](../../sensitivitylabel/) hinzugefügt wurde.

## Siehe auch

* Aufzählung [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [ISensitivityLabel](../../isensitivitylabel/)
* Klasse [String](../../../system/string/)
* Klasse [Guid](../../../system/guid/)
* Klasse [SensitivityLabelCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)