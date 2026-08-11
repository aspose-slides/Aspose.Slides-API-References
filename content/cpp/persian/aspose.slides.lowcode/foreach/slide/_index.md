---
title: Slide()
second_title: Aspose.Slides برای مرجع API C++
description: "هر ForEach::Slide را در Presentation تکرار کنید."
type: docs
weight: 1
url: /fa/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) متد


تکرار هر [ForEach::Slide](./) در [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) برای تکرار اسلایدها |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback که برای هر اسلاید فراخوانی می‌شود |
## توضیحات




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```




## مراجعه

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* کلاس [Presentation](../../../aspose.slides/presentation/)
* کلاس [ForEach](../)
* فضای‌نام [Aspose::Slides::LowCode](../../)
* کتابخانه [Aspose.Slides](../../../)