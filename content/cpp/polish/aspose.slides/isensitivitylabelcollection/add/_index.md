---
title: Add()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Dodaje etykietę wrażliwości na końcu kolekcji.
type: docs
weight: 27
url: /pl/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metoda


Dodaje etykietę wrażliwości na końcu kolekcji.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Identyfikator etykiety wrażliwości. |
| siteId | [System::Guid](../../../system/guid/) | Identyfikator witryny Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Flaga wskazuje, czy etykieta wrażliwości jest włączona. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Metoda przypisania etykiety wrażliwości. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metoda


Dodaje [SensitivityLabel](../../sensitivitylabel/) do kolekcji.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
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
* Class [ISensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)