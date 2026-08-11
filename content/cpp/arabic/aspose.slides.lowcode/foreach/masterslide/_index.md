---
title: MasterSlide()
second_title: مرجع API Aspose.Slides للغة C++
description: "تكرار كل ForEach::MasterSlide في Presentation."
type: docs
weight: 14
url: /ar/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) طريقة


تكرار كل [ForEach::MasterSlide](./) في [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) لتكرار شرائح الماستر |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | دالة رد النداء ستُستدعى لكل شريحة رئيسية |
## ملاحظات




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* فئة [Presentation](../../../aspose.slides/presentation/)
* فئة [ForEach](../)
* مساحة الاسم [Aspose::Slides::LowCode](../../)
* مكتبة [Aspose.Slides](../../../)