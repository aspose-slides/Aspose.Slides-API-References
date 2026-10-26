---
title: get_Masters()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan daftar semua slide master yang didefinisikan dalam presentasi. Hanya-baca IMasterSlideCollection.
type: docs
weight: 118
url: /id/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() metode


Mengembalikan daftar semua slide master yang didefinisikan dalam presentasi. Hanya-baca [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Catatan


Contoh berikut menunjukkan cara menambahkan [Images](../../images/) ke Master [Slides](../../) PowerPoint [Presentation](../). 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
 Contoh berikut menunjukkan cara mengubah warna latar belakang slide master PowerPoint [Presentation](../). 
```cpp
// Membuat instance kelas Presentation yang mewakili file presentasi
auto pres = System::MakeObject<Presentation>();

// Set warna latar belakang Master ISlide menjadi Hijau Hutan
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Tuliskan presentasi ke disk
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
 Contoh berikut menunjukkan cara menambahkan tata letak slide ke PowerPoint [Presentation](../). 
```cpp
// Membuat instance kelas Presentation yang mewakili file presentasi
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Mencoba mencari berdasarkan tipe slide tata letak
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Situasi ketika presentasi tidak mengandung beberapa jenis tata letak.
    // File presentasi hanya berisi jenis tata letak Blank dan Custom.
    // Namun slide tata letak dengan tipe Custom memiliki nama slide yang berbeda,
    // seperti "Title", "Title and Content", dll. Dan dapat menggunakan ini
    // nama untuk pemilihan slide tata letak.
    // Juga memungkinkan untuk menggunakan kumpulan tipe bentuk placeholder. Sebagai contoh,
    // Slide Judul harus hanya memiliki tipe placeholder Title, dll.
    for (auto&& titleAndObjectLayoutSlide : layoutSlides)
    {
        if (titleAndObjectLayoutSlide->get_Name() == u"Title and Object")
        {
            layoutSlide = titleAndObjectLayoutSlide;
            break;
        }
    }

    if (layoutSlide == nullptr)
    {
        for (auto&& titleLayoutSlide : layoutSlides)
        {
            if (titleLayoutSlide->get_Name() == u"Title")
            {
                layoutSlide = titleLayoutSlide;
                break;
            }
        }

        if (layoutSlide == nullptr)
        {
            layoutSlide = layoutSlides->GetByType(SlideLayoutType::Blank);
            if (layoutSlide == nullptr)
            {
                layoutSlide = layoutSlides->Add(SlideLayoutType::TitleAndObject, u"Title and Object");
            }
        }
    }
}

// Menambahkan slide kosong dengan slide tata letak yang ditambahkan
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Simpan presentasi
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMasterSlideCollection](../../imasterslidecollection/)
* Kelas [Presentation](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)