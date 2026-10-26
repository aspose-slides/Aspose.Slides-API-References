---
title: Add()
second_title: Aspose.Slides dla C++ – Referencja API
description: Dodaje etykietę poufności na końcu kolekcji.
type: docs
weight: 27
url: /pl/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method

Dodaje etykietę poufności na końcu kolekcji.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Identyfikator etykiety poufności. |
| siteId | [System::Guid](../../../system/guid/) | Identyfikator witryny Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Flaga wskazuje, czy etykieta poufności jest włączona. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Metoda przypisania etykiety poufności. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method

Dodaje [SensitivityLabel](../../sensitivitylabel/) do kolekcji.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Obiekt [SensitivityLabel](../../sensitivitylabel/) do dodania na końcu kolekcji. |

### Wartość zwracana

Indeks, pod którym [SensitivityLabel](../../sensitivitylabel/) został dodany.

## Zobacz także

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [SensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)