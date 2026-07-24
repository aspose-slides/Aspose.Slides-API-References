---
title: get_Masters()
second_title: Aspose.Slides C++ API Referansı
description: Sunumda tanımlanan tüm master slaytların bir listesini döndürür. Yalnızca okunur IMasterSlideCollection.
type: docs
weight: 118
url: /tr/aspose.slides/presentation/get_masters/
---
## Presentation::get_Masters() method

Sunumda tanımlanan tüm master slaytların bir listesini döndürür. Yalnızca okunur [IMasterSlideCollection](../../imasterslidecollection/).

```cpp
System::SharedPtr<IMasterSlideCollection> Aspose::Slides::Presentation::get_Masters() override
```

## Açıklamalar

Aşağıdaki örnekler, [Images](../../images/) öğesini PowerPoint [Presentation](../)'nin Master [Slides](../../)'ine eklemenin nasıl yapılacağını gösterir.
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);
auto masterSlide = slide->get_LayoutSlide()->get_MasterSlide();

auto image = pres->get_Images()->AddImage(System::IO::File::ReadAllBytes(u"image.png"));
masterSlide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
pres->Save(u"pres.pptx", SaveFormat::Pptx);
```
Aşağıdaki örnekler, PowerPoint [Presentation](../)'nin master slaytının arka plan rengini nasıl değiştireceğinizi gösterir.
```cpp
// Sunum dosyasını temsil eden Presentation sınıfını örnekle
auto pres = System::MakeObject<Presentation>();

// Master ISlide'ın arka plan rengini Orman Yeşili olarak ayarla
auto masterSlide = pres->get_Masters()->idx_get(0);
auto background = masterSlide->get_Background();
background->set_Type(BackgroundType::OwnBackground);
background->get_FillFormat()->set_FillType(FillType::Solid);
background->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
// Sunumu diske yaz
pres->Save(u"SetSlideBackgroundMaster_out.pptx", SaveFormat::Pptx);
```
Aşağıdaki örnekler, PowerPoint [Presentation](../)'ye slayt düzeni eklemenin nasıl yapılacağını gösterir.
```cpp
// Sunum dosyasını temsil eden Presentation sınıfını oluştur
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Düzen slayt tipine göre aramayı dene
auto layoutSlides = presentation->get_Masters()->idx_get(0)->get_LayoutSlides();
auto layoutSlide = System::ObjectExt::Coalesce(
    layoutSlides->GetByType(SlideLayoutType::TitleAndObject),
    [&](){ return layoutSlides->GetByType(SlideLayoutType::Title); });

if (layoutSlide == nullptr)
{
    // Bir sunumun bazı düzen tiplerini içermediği durum.
    // Sunum dosyası yalnızca Boş ve Özel düzen tiplerini içerir.
    // Ancak Özel tipli düzen slaytlarının farklı slayt adları vardır,
    // "Title", "Title and Content" gibi ve bunları kullanmak mümkündür
    // düzen slayt seçimi için isimleri.
    // Ayrıca yer tutucu şekil tipleri kümesini kullanmak da mümkündür. Örneğin,
    // Başlık slaytı sadece Başlık yer tutucu tipine sahip olmalıdır, vb.
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

// Eklenen düzen slaytıyla boş slayt ekleniyor
presentation->get_Slides()->InsertEmptySlide(0, layoutSlide);
// Sunumu kaydet
presentation->Save(u"AddLayoutSlides_out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMasterSlideCollection](../../imasterslidecollection/)
* Sınıf [Presentation](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)