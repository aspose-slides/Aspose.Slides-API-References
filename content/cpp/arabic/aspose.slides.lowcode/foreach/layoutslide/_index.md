---
title: LayoutSlide()
second_title: Aspose.Slides للغة C++ مرجع API
description: "تكرار كل ForEach::LayoutSlide في العرض التقديمي."
type: docs
weight: 27
url: /ar/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachLayoutSlideCallback) طريقة

تكرار كل [ForEach::LayoutSlide](./) في [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) لتكرار شرائح التخطيط |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | دالة رد النداء التي سيتم استدعاؤها لكل شريحة تخطيط |

## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* فئة [Presentation](../../../aspose.slides/presentation/)
* فئة [ForEach](../)
* مساحة أسماء [Aspose::Slides::LowCode](../../)
* مكتبة [Aspose.Slides](../../../)