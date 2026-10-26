---
title: Add()
second_title: Aspose.Slides C++ API referencia
description: Hozzáadja az érzékenységi címkét a gyűjtemény végéhez.
type: docs
weight: 27
url: /hu/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metódus

Hozzáadja az érzékenységi címkét a gyűjtemény végéhez.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Az érzékenységi címke azonosítója. |
| siteId | [System::Guid](../../../system/guid/) | Az Azure Active Directory (Azure AD) webhely azonosítója. |
| isEnabled | **bool** | Jelző, amely jelzi, hogy az érzékenységi címke engedélyezve van-e. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Az érzékenységi címke hozzárendelési módja. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metódus

Hozzáad egy [SensitivityLabel](../../sensitivitylabel/) a gyűjteményhez.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | A [SensitivityLabel](../../sensitivitylabel/) objektum, amelyet a gyűjtemény végén adunk hozzá. |

### Visszatérési érték

Az index, ahol a [SensitivityLabel](../../sensitivitylabel/) hozzá lett adva.

## Lásd még

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [ISensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)