---
title: Slide()
second_title: Aspose.Slides for C++ API Referansı
description: "Sunumdaki her ForEach::Slide'i yineleyin."
type: docs
weight: 1
url: /tr/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) metod

Her [ForEach::Slide](./)'i [Presentation](../../../aspose.slides/presentation/) içinde yinele.

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) slaytları yinelemek için |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Her slayt için çağrılacak geri arama |

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)