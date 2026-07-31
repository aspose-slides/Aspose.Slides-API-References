---
title: set_GridSpacing()
second_title: Aspose.Slides untuk Referensi API C++
description: Menetapkan jarak kisi yang harus digunakan untuk kisi yang mendasari dokumen presentasi, dalam poin. Tulis float.
type: docs
weight: 105
url: /id/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) metode

Menetapkan jarak kisi yang harus digunakan untuk kisi yang mendasari dokumen presentasi, dalam poin. Tulis **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## Keterangan

Nilai jarak kisi harus berupa angka positif. Kisaran nilai tipikal adalah dari 1 mm (2.8349607 poin) hingga 2 inci (144 poin).

Kode contoh berikut menunjukkan cara mengubah jarak kisi dalam presentasi PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [IViewProperties](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)