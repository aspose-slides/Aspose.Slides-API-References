---
title: GetSensitivityLabels()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan array label sensitivitas dari properti dokumen khusus (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /id/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() metode

Mendapatkan array label sensitivitas dari properti dokumen khusus (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## Remarks

Kode berikut menunjukkan cara memindahkan informasi label sensitivitas dari properti dokumen khusus ke koleksi SensitivityLabels modern: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Dapatkan label sensitivitas dari properti dokumen khusus
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Tambahkan label ke koleksi
    // Di sini Anda dapat menambahkan pemeriksaan untuk validitas informasi label (label tersedia, dll)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISensitivityLabel](../../isensitivitylabel/)
* Kelas [IDocumentProperties](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)