---
title: Add()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan label sensitivitas di akhir koleksi.
type: docs
weight: 27
url: /id/aspose.slides/sensitivitylabelcollection/add/
---
## SensitivityLabelCollection::Add(System::String, System::Guid, bool, SensitivityLabelAssignmentType) metode


Menambahkan label sensitivitas di akhir koleksi.

```cpp
System::SharedPtr<ISensitivityLabel> Aspose::Slides::SensitivityLabelCollection::Add(System::String id, System::Guid siteId, bool isEnabled, SensitivityLabelAssignmentType methodType) override
```


### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| id | [System::String](../../../system/string/) | ID label sensitivitas. |
| siteId | [System::Guid](../../../system/guid/) | Pengidentifikasi situs Azure Active Directory (Azure AD). |
| isEnabled | **bool** | Bendera yang menunjukkan apakah label sensitivitas diaktifkan. |
| methodType | [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/) | Metode penugasan untuk label sensitivitas. |

## SensitivityLabelCollection::Add(System::SharedPtr\<ISensitivityLabel\>) metode


Menambahkan [SensitivityLabel](../../sensitivitylabel/) ke koleksi.

```cpp
int32_t Aspose::Slides::SensitivityLabelCollection::Add(System::SharedPtr<ISensitivityLabel> label) override
```


### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| label | [System::SharedPtr](../../../system/sharedptr/)\<[ISensitivityLabel](../../isensitivitylabel/)\> | Objek [SensitivityLabel](../../sensitivitylabel/) yang akan ditambahkan di akhir koleksi. |

### Nilai Kembali

Indeks di mana [SensitivityLabel](../../sensitivitylabel/) ditambahkan.

## Lihat Juga

* Enum [SensitivityLabelAssignmentType](../../sensitivitylabelassignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISensitivityLabel](../../isensitivitylabel/)
* Kelas [String](../../../system/string/)
* Kelas [Guid](../../../system/guid/)
* Kelas [SensitivityLabelCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)