---
title: Add()
second_title: Aspose.Slides pro C++ – reference API
description: Přidá štítek citlivosti na konec kolekce.
type: docs
weight: 27
url: /cs/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metoda

Přidá štítek citlivosti na konec kolekce.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Identifikátor štítku citlivosti. |
| siteId | [System::Guid](../../../system/guid/) | Identifikátor webu Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Příznak udává, zda je štítek citlivosti povolen. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Metoda přiřazení pro štítek citlivosti. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metoda

Přidá [SensitivityLabel](../../sensitivitylabel/) do kolekce.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Objekt [SensitivityLabel](../../sensitivitylabel/), který bude přidán na konec kolekce. |

### Návratová hodnota

Index, kde byl [SensitivityLabel](../../sensitivitylabel/) přidán.

## Viz také

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISensitivityLabel](../../isensitivitylabel/)
* Třída [String](../../../system/string/)
* Třída [Guid](../../../system/guid/)
* Třída [SensitivityLabelCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)