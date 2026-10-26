---
title: LayoutSlide()
second_title: مستندات API Aspose.Slides برای C++
description: "هر ForEach::LayoutSlide را در Presentation تکرار کنید."
type: docs
weight: 27
url: /fa/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachLayoutSlideCallback) متد

هر [ForEach::LayoutSlide](./) در [Presentation](../../../aspose.slides/presentation/) تکرار می‌شود.

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) برای تکرار اسلایدهای چیدمان |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | Callback که برای هر اسلاید چیدمان فراخوانی می‌شود |
## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* تعریف نوع [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* کلاس [ForEach](../)
* فضای‌نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)