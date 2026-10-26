---
title: get_Slides()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mengembalikan daftar semua slide yang didefinisikan dalam presentasi. Hanya-baca ISlideCollection.
type: docs
weight: 53
url: /id/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() metode

Mengembalikan daftar semua slide yang didefinisikan dalam presentasi. Hanya-baca [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Catatan

Contoh berikut menunjukkan cara mengatur warna latar belakang slide pada PowerPoint [Presentation](../). 
```cpp
// Instansiasi kelas Presentation yang mewakili file presentasi
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// Set the background color of the first ISlide to Blue
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 Contoh berikut menunjukkan cara mengatur gambar latar belakang slide pada PowerPoint [Presentation](../). 
```cpp
// Instansiasi kelas Presentation yang mewakili file presentasi
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Atur latar belakang dengan Gambar
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Atur gambar
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Tambahkan gambar ke koleksi gambar presentasi
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Tuliskan presentasi ke disk
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 Contoh berikut menunjukkan cara menambahkan transisi slide [Presentation](../). 
```cpp
// Instansiasi kelas Presentation untuk memuat file presentasi sumber
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Terapkan transisi tipe lingkaran pada slide 1
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Terapkan transisi tipe sisir pada slide 2
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Tulis presentasi ke disk
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 Contoh berikut menunjukkan cara menambahkan Transisi slide lanjutan. 
```cpp
// Instansiasi kelas Presentation yang mewakili file presentasi
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Terapkan transisi tipe lingkaran pada slide 1
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Atur waktu transisi menjadi 3 detik
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Terapkan transisi tipe sisir pada slide 2
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Atur waktu transisi menjadi 5 detik
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Terapkan transisi tipe zoom pada slide 3
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// Atur waktu transisi menjadi 7 detik
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Tulis presentasi ke disk
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlideCollection](../../islidecollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)