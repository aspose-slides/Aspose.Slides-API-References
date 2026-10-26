---
title: LayoutSlide()
second_title: Aspose.Slides C++ API Referansı
description: "Sunum içinde her ForEach::LayoutSlide'i yineleyin."
type: docs
weight: 27
url: /tr/aspose.slides.lowcode/foreach/layoutslide/
---
## ForEach::LayoutSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachLayoutSlideCallback) metodu

Her bir [ForEach::LayoutSlide](./)'yi [Presentation](../../../aspose.slides/presentation/) içinde yineleyin.

```cpp
static void Aspose::Slides::LowCode::ForEach::LayoutSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachLayoutSlideCallback forEachLayoutSlide)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) düzen kaydıraklarını yinelemek için |
| forEachLayoutSlide | [ForEach::ForEachLayoutSlideCallback](../foreachlayoutslidecallback/) | Her bir düzen kaydırak için çağrılacak geri arama |

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<LayoutSlide> layoutSlide, int32_t index)>([](SharedPtr<LayoutSlide> layoutSlide, int32_t index)
{
    layoutSlide->set_Name(String::Format(u"LayoutSlide #{0}", index));
});

ForEach::LayoutSlide(pres, callback);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachLayoutSlideCallback](../foreachlayoutslidecallback/)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* Sınıf [ForEach](../)
* İsim Uzayı [Aspose::Slides::LowCode](../../)
* Kütüphane [Aspose.Slides](../../../)