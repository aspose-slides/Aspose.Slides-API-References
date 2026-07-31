---
title: get_SlideSize()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan objek ukuran slide. Hanya-baca ISlideSize.
type: docs
weight: 79
url: /id/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() metode

Mengembalikan objek ukuran slide. Hanya-baca [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Keterangan

The following example shows how to change the slide size in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 The following example shows how to set slide size with respect to content scaling for a PowerPoint [Presentation](../). 
```cpp
// Membuat objek Presentation yang mewakili file presentasi
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Setel ukuran slide presentasi yang dihasilkan agar sama dengan sumber
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// Metode SetSize digunakan untuk mengatur ukuran slide dengan menskala konten agar pas
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// Metode SetSize digunakan untuk mengatur ukuran slide dengan memaksimalkan ukuran konten
// Simpan Presentation ke disk
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to specifying custom slide sizes in a PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// Ukuran kertas A4
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISlideSize](../../islidesize/)
* Kelas [Presentation](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)