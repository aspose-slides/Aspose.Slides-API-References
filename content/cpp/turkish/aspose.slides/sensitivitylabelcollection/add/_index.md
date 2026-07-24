---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Duyarlılık etiketini koleksiyonun sonuna ekler.
type: docs
weight: 27
url: /tr/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metot


Koleksiyonun sonuna duyarlılık etiketini ekler.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Duyarlılık etiketinin kimliği. |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) site tanımlayıcısı. |
| isEnabled | **bool** | Duyarlılık etiketinin etkin olup olmadığını belirten bayrak. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Duyarlılık etiketi için atama yöntemi. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metot


[SensitivityLabel](../../sensitivitylabel/)'i koleksiyona ekler.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Koleksiyonun sonuna eklenecek [SensitivityLabel](../../sensitivitylabel/) nesnesi. |

### Dönüş Değeri

[SensitivityLabel](../../sensitivitylabel/)'in eklendiği indeks.

## Ayrıca Bakınız

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISensitivityLabel](../../isensitivitylabel/)
* Sınıf [String](../../../system/string/)
* Sınıf [Guid](../../../system/guid/)
* Sınıf [SensitivityLabelCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)