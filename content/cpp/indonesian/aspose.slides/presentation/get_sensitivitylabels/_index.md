---
title: get_SensitivityLabels()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan koleksi label sensitivitas yang diterapkan pada dokumen presentasi. Read-only ISensitivityLabelCollection.
type: docs
weight: 378
url: /id/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() metode


Mengembalikan koleksi label sensitivitas yang diterapkan pada dokumen presentasi. Hanya baca [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Catatan



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Cetak label yang diterapkan
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Tambahkan label baru
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Dapatkan Id label sensitivitas dari kebijakan
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Dapatkan pengenal situs Azure AD dari kebijakan
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Kelas [Presentation](../)
* Ruang nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)