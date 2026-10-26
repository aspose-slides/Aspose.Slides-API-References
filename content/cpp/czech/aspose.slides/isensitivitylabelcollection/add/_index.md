---
title: Add()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá štítek citlivosti na konec kolekce.
type: docs
weight: 27
url: /cs/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metoda

Přidá štítek citlivosti na konec kolekce.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Identifikátor štítku citlivosti. |
| siteId | [System::Guid](../../../system/guid/) | Identifikátor webu Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Příznak označuje, zda je štítek citlivosti povolen. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Metoda přiřazení pro štítek citlivosti. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metoda

Přidá [SensitivityLabel](../../sensitivitylabel/) do kolekce.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Objekt [SensitivityLabel](../../sensitivitylabel/) který bude přidán na konec kolekce. |

### Návratová hodnota

Index, na kterém byl [SensitivityLabel](../../sensitivitylabel/) přidán.

## Viz také

* Výčet [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [ISensitivityLabel](../../isensitivitylabel/)
* Třída [String](../../../system/string/)
* Třída [Guid](../../../system/guid/)
* Třída [ISensitivityLabelCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)