---
title: set_GridSpacing()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan jarak kisi yang harus digunakan untuk kisi yang mendasari dokumen presentasi, dalam poin. Tulis float.
type: docs
weight: 105
url: /id/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) metode

Menetapkan jarak kisi yang harus digunakan untuk kisi yang mendasari dokumen presentasi, dalam poin. Tulis **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
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
* Perpustakaan [Aspose.Slides](../../../)