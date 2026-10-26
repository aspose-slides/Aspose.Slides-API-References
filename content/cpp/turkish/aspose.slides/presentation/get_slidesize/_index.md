---
title: get_SlideSize()
second_title: Aspose.Slides for C++ API Referansı
description: Slide boyutu nesnesini döndürür. Salt okunur ISlideSize.
type: docs
weight: 79
url: /tr/aspose.slides/presentation/get_slidesize/
---
## Presentation::get_SlideSize() yöntemi


Slide boyutu nesnesini döndürür. Salt okunur [ISlideSize](../../islidesize/).

```cpp
System::SharedPtr<ISlideSize> Aspose::Slides::Presentation::get_SlideSize() override
```

## Açıklamalar


Aşağıdaki örnek, bir PowerPoint [Presentation](../)'de slayt boyutunu nasıl değiştireceğinizi gösterir.
```cpp
auto pres = System::MakeObject<Presentation>(u"pres-4x3-aspect-ratio.pptx");

pres->get_SlideSize()->SetSize(SlideSizeType::OnScreen16x9, SlideSizeScaleType::DoNotScale);
pres->Save(u"pres-4x3-aspect-ratio.pptx", SaveFormat::Pptx);
```
 The aşağıdaki örnek, bir PowerPoint [Presentation](../) için içerik ölçeklemesine göre slayt boyutunu nasıl ayarlayacağınızı gösterir.
```cpp
// Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
auto presentation = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto auxPresentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// Oluşturulan sunumların slayt boyutunu kaynağınkine ayarla
presentation->get_SlideSize()->SetSize(540.0f, 720.0f, SlideSizeScaleType::EnsureFit);

// SetSize yöntemi, içerik ölçeğiyle slayt boyutunu ayarlamak ve sığmasını sağlamak için kullanılır
presentation->get_SlideSize()->SetSize(SlideSizeType::A4Paper, SlideSizeScaleType::Maximize);

// SetSize yöntemi, içeriğin boyutunu en üst düzeye çıkarmak için slayt boyutunu ayarlamakta kullanılır
// Sunumu diske kaydet
auxPresentation->Save(u"Set_Size_Type_out.pptx", SaveFormat::Pptx);
```
 The aşağıdaki örnek, bir PowerPoint [Presentation](../) içinde özel slayt boyutlarını nasıl belirleyeceğinizi gösterir.
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
pres->get_SlideSize()->SetSize(780.0f, 540.0f, SlideSizeScaleType::DoNotScale);

// A4 kağıt boyutu
pres->Save(u"pres-a4-slide-size.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlideSize](../../islidesize/)
* Sınıf [Presentation](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)