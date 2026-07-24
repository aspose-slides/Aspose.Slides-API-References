---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun sonuna duyarlılık etiketini ekler.
type: docs
weight: 27
url: /tr/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metod

Koleksiyonun sonuna duyarlılık etiketini ekler.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | Duyarlılık etiketinin kimliği. |
| siteId | [System::Guid](../../../system/guid/) | Azure Active Directory (Azure AD) site tanımlayıcısı. |
| isEnabled | **bool** | Bayrak, duyarlılık etiketinin etkin olup olmadığını gösterir. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Duyarlılık etiketi için atama yöntemi. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metod

Koleksiyona bir [SensitivityLabel](../../sensitivitylabel/) ekler.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Koleksiyonun sonunda eklenecek [SensitivityLabel](../../sensitivitylabel/) nesnesi. |

### Dönüş Değeri

[SensitivityLabel](../../sensitivitylabel/)'nin eklendiği dizin.

## İlgili

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISensitivityLabel](../../isensitivitylabel/)
* Sınıf [String](../../../system/string/)
* Sınıf [Guid](../../../system/guid/)
* Sınıf [ISensitivityLabelCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)