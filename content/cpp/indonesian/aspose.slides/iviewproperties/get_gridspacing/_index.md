---
title: get_GridSpacing()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan jarak kisi yang harus digunakan untuk kisi yang mendasari dokumen presentasi, dalam poin. Baca float.
type: docs
weight: 92
url: /id/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() metode

Mengembalikan jarak kisi yang harus digunakan untuk kisi yang mendasari dokumen presentasi, dalam poin. Baca **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
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
* RuangNama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)