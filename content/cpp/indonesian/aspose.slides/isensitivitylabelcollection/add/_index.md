---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan label sensitivitas di akhir koleksi.
type: docs
weight: 27
url: /id/aspose.slides/isensitivitylabelcollection/add/
---
## ISensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) method

Menambahkan label sensitivitas di akhir koleksi.

```cpp
virtual System::SharedPtr<ISensitivityLabel> Aspose::Slides::ISensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | ID label sensitivitas. |
| siteId | [System::Guid](../../../system/guid/) | Pengidentifikasi situs Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Bendera menunjukkan apakah label sensitivitas diaktifkan. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Metode penugasan untuk label sensitivitas. |

## ISensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) method

Menambahkan [SensitivityLabel](../../sensitivitylabel/) ke koleksi.

```cpp
virtual int32_t Aspose::Slides::ISensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Objek [SensitivityLabel](../../sensitivitylabel/) yang akan ditambahkan di akhir koleksi. |

### Nilai Kembalian

Indeks tempat [SensitivityLabel](../../sensitivitylabel/) ditambahkan.

## Lihat Juga

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISensitivityLabel](../../isensitivitylabel/)
* Class [String](../../../system/string/)
* Class [Guid](../../../system/guid/)
* Class [ISensitivityLabelCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)