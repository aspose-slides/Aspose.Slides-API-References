---
title: ForEach
second_title: Aspose.Slides for C++ API Referansı
description: Farklı Presentation model nesneleri üzerinde yineleme yapmak için tasarlanmış bir grup yöntemi temsil eder. Bu yöntemler, bazı Presentation öğelerinin biçimlendirmesini veya içeriğini yinelemek ve değiştirmek istiyorsanız faydalı olabilir, ör. her bölümün biçimlendirmesini değiştirmek.
type: docs
weight: 40
url: /tr/aspose.slides.lowcode/foreach/
---
## ForEach sınıfı

Farklı [Presentation](../../aspose.slides/presentation/) model nesneleri üzerinde yineleme yapmak için tasarlanmış bir grup yöntemi temsil eder. Bu yöntemler, bazı [Presentation](../../aspose.slides/presentation/) öğelerinin biçimlendirmesini veya içeriğini yinelemek ve değiştirmek istiyorsanız faydalı olabilir, ör. her bölümün biçimlendirmesini değiştirmek.

```cpp
class ForEach
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | Her bir [ForEach::LayoutSlide](./layoutslide/) öğesini [Presentation](../../aspose.slides/presentation/) içinde yinele. |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | Her bir [ForEach::MasterSlide](./masterslide/) öğesini [Presentation](../../aspose.slides/presentation/) içinde yinele. |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Her bir [ForEach::Paragraph](./paragraph/) öğesini [Presentation](../../aspose.slides/presentation/) içinde yinele. |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | Her bir [ForEach::Paragraph](./paragraph/) öğesini [Presentation](../../aspose.slides/presentation/) içinde yinele. |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Her bir [ForEach::Portion](./portion/) öğesini [Presentation](../../aspose.slides/presentation/) içinde yinele. |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | Her bir [ForEach::Portion](./portion/) öğesini [Presentation](../../aspose.slides/presentation/) içinde yinele. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Her bir [ForEach::Shape](./shape/) öğesini [Presentation](../../aspose.slides/presentation/) içinde yinele. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Her bir [ForEach::Shape](./shape/) öğesini [Presentation](../../aspose.slides/presentation/) içinde yinele. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | Her bir [ForEach::Shape](./shape/) öğesini [BaseSlide](../../aspose.slides/baseslide/) içinde yinele. |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | Her bir [ForEach::Slide](./slide/) öğesini [Presentation](../../aspose.slides/presentation/) içinde yinele. |

## Typedef'ler

| Tip Tanımı | Açıklama |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | Her bir [ForEach::Slide](./slide/) öğesi [Presentation](../../aspose.slides/presentation/) içinde çağrılacak geri çağırma. |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | Her bir [ForEach::MasterSlide](./masterslide/) öğesi [Presentation](../../aspose.slides/presentation/) içinde çağrılacak geri çağırma. |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | Her bir [ForEach::LayoutSlide](./layoutslide/) öğesi [Presentation](../../aspose.slides/presentation/) içinde çağrılacak geri çağırma. |
| [ForEachShapeCallback](./foreachshapecallback/) | Her bir [ForEach::Shape](./shape/) öğesi [Presentation](../../aspose.slides/presentation/) içinde çağrılacak geri çağırma. |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | Her bir [ForEach::Paragraph](./paragraph/) öğesi [BaseSlide](../../aspose.slides/baseslide/) üzerinde çağrılacak geri çağırma. |
| [ForEachPortionCallback](./foreachportioncallback/) | Her bir [ForEach::Portion](./portion/) öğesi [ForEach::Paragraph](./paragraph/) içinde [BaseSlide](../../aspose.slides/baseslide/) üzerinde çağrılacak geri çağırma. |

## Açıklamalar

```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"Times New Roman"));
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(presentation, callback);

presentation->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Bakınız

* Ad alanı [Aspose::Slides::LowCode](../)
* Kütüphane [Aspose.Slides](../../)