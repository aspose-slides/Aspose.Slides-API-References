---
title: get_GridSpacing()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan jarak kisi yang harus digunakan untuk kisi di bawah dokumen presentasi, dalam poin. Baca float.
type: docs
weight: 92
url: /id/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() metode

Mengembalikan jarak kisi yang harus digunakan untuk kisi di bawah dokumen presentasi, dalam poin. Baca **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Catatan

Nilai jarak kisi harus berupa angka positif. Rentang nilai tipikal adalah dari 1 mm (2.8349607 poin) hingga 2 inci (144 poin). 

Kode contoh berikut menunjukkan cara mengubah jarak kisi dalam presentasi PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Kelas [ViewProperties](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)