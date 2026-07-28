---
title: Add()
second_title: Aspose.Slides C++ API referenciája
description: Hozzáadja az érzékenységi címkét a gyűjtemény végéhez.
type: docs
weight: 27
url: /hu/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metódus


Hozzáadja az érzékenységi címkét a gyűjtemény végéhez.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Az érzékenységi címke azonosítója. |
| siteId | [System::Guid](../../../system/guid/) | Az Azure Active Directory (Azure AD) webhely azonosítója. |
| isEnabled | **bool** | A jelző jelzi, hogy az érzékenységi címke engedélyezve van-e. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Az érzékenységi címke hozzárendelési módszere. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metódus


Hozzáad egy [SensitivityLabel](../../sensitivitylabel/) a gyűjteményhez.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | A [SensitivityLabel](../../sensitivitylabel/) objektum, amely a gyűjtemény végén kerül hozzáadásra. |

### Visszatérési érték

Az index, ahol a [SensitivityLabel](../../sensitivitylabel/) hozzá lett adva.

## Lásd még

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISensitivityLabel](../../isensitivitylabel/)
* Osztály [String](../../../system/string/)
* Osztály [Guid](../../../system/guid/)
* Osztály [SensitivityLabelCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)