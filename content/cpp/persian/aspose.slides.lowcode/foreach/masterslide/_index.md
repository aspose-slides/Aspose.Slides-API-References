---
title: MasterSlide()
second_title: Aspose.Slides برای C++ مرجع API
description: "هر ForEach::MasterSlide را در Presentation تکرار کنید."
type: docs
weight: 14
url: /fa/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) متد

هر [ForEach::MasterSlide](./) را در [Presentation](../../../aspose.slides/presentation/) تکرار کنید.

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) برای تکرار اسلایدهای اصلی |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | Callback که برای هر master slide فراخوانی خواهد شد |

## توضیحات

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## مراجع مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* تعریف‌نوع [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* کلاس [ForEach](../)
* فضای‌نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)