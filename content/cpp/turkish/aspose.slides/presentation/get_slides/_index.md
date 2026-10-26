---
title: get_Slides()
second_title: Aspose.Slides için C++ API Referansı
description: Sunumda tanımlanan tüm slaytların bir listesini döndürür. Salt okunur ISlideCollection.
type: docs
weight: 53
url: /tr/aspose.slides/presentation/get_slides/
---
## Presentation::get_Slides() metod


Sunumda tanımlanan tüm slaytların bir listesini döndürür. Salt okunur [ISlideCollection](../../islidecollection/).

```cpp
System::SharedPtr<ISlideCollection> Aspose::Slides::Presentation::get_Slides() override
```

## Açıklamalar


Aşağıdaki örnek, PowerPoint [Presentation](../) slaytların arka plan rengini nasıl ayarlayacağını gösterir.
```cpp
// Sunum dosyasını temsil eden Presentation sınıfının bir örneğini oluştur
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

// İlk ISlide'ın arka plan rengini Maviye ayarla
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Solid);
slide->get_Background()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Blue());
pres->Save(u"ContentBG_out.pptx", SaveFormat::Pptx);
```
 Aşağıdaki örnek, PowerPoint [Presentation](../) slaytların arka plan görüntüsünü nasıl ayarlayacağını gösterir.
```cpp
// Sunum dosyasını temsil eden Presentation sınıfının bir örneğini oluştur
auto pres = System::MakeObject<Presentation>(u"SetImageAsBackground.pptx");
auto slide = pres->get_Slides()->idx_get(0);

// Görüntü ile arka planı ayarla
slide->get_Background()->set_Type(BackgroundType::OwnBackground);
slide->get_Background()->get_FillFormat()->set_FillType(FillType::Picture);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->set_PictureFillMode(PictureFillMode::Stretch);
// Resmi ayarla
auto img = System::ExplicitCast<System::Drawing::Image>(System::MakeObject<System::Drawing::Bitmap>(dataDir + u"Tulips.jpg"));
// Görüntüyü sunumun görüntüler koleksiyonuna ekle
auto imgx = pres->get_Images()->AddImage(img);
slide->get_Background()->get_FillFormat()->get_PictureFillFormat()->get_Picture()->set_Image(imgx);
// Sunumu diske kaydet
pres->Save(u"ContentBG_Img_out.pptx", SaveFormat::Pptx);
```
 Aşağıdaki örnek, [Presentation](../) slayt geçişi eklemeyi nasıl yapacağını gösterir.
```cpp
// Kaynak sunum dosyasını yüklemek için Presentation sınıfının bir örneğini oluştur
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");

// Slayt 1'e daire tipi geçiş uygula
presentation->get_Slides()->idx_get(0)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// Slayt 2'ye tarak tipi geçiş uygula
presentation->get_Slides()->idx_get(1)->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// Sunumu diske kaydet
presentation->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```
 Aşağıdaki örnek, gelişmiş slayt geçişi eklemeyi gösterir.
```cpp
// Sunum dosyasını temsil eden Presentation sınıfının bir örneğini oluştur
auto pres = System::MakeObject<Presentation>(u"BetterSlideTransitions.pptx");

auto slide1 = pres->get_Slides()->idx_get(0);
auto slide2 = pres->get_Slides()->idx_get(1);
auto slide3 = pres->get_Slides()->idx_get(2);

// Slayt 1'e daire tipi geçiş uygula
slide1->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Circle);
// 3 saniye geçiş süresi ayarla
slide1->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide1->get_SlideShowTransition()->set_AdvanceAfterTime(3000);
// Slayt 2'ye tarak tipi geçiş uygula
slide2->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Comb);
// 5 saniye geçiş süresi ayarla
slide2->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide2->get_SlideShowTransition()->set_AdvanceAfterTime(5000);
// Slayt 3'e yakınlaştırma tipi geçiş uygula
slide3->get_SlideShowTransition()->set_Type(SlideShow::TransitionType::Zoom);
// 7 saniye geçiş süresi ayarla
slide3->get_SlideShowTransition()->set_AdvanceOnClick(true);
slide3->get_SlideShowTransition()->set_AdvanceAfterTime(7000);
// Sunumu diske kaydet
pres->Save(u"SampleTransition_out.pptx", SaveFormat::Pptx);
```

## Diğer Bölümler

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlideCollection](../../islidecollection/)
* Sınıf [Presentation](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)