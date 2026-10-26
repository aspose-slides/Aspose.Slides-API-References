---
title: MasterSlide()
second_title: Aspose.Slides for C++ API Referansı
description: "Presentation içindeki her ForEach::MasterSlide öğesini yineleyin."
type: docs
weight: 14
url: /tr/aspose.slides.lowcode/foreach/masterslide/
---
## ForEach::MasterSlide(System::SharedPtr\<Presentation\>, ForEach::ForEachMasterSlideCallback) metot

Her bir [ForEach::MasterSlide](./) öğesini [Presentation](../../../aspose.slides/presentation/) içinde yineleyin.

```cpp
static void Aspose::Slides::LowCode::ForEach::MasterSlide(System::SharedPtr<Presentation> pres, ForEach::ForEachMasterSlideCallback forEachMasterSlide)
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) master slaytları yinelemek için |
| forEachMasterSlide | [ForEach::ForEachMasterSlideCallback](../foreachmasterslidecallback/) | Her bir master slayt için çağrılacak geri arama |

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<MasterSlide> slide, int32_t index)>([](SharedPtr<MasterSlide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"MasterSlide #{0}", index));
});

ForEach::MasterSlide(pres, callback);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachMasterSlideCallback](../foreachmasterslidecallback/)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* Sınıf [ForEach](../)
* Ad alanı [Aspose::Slides::LowCode](../../)
* Kütüphane [Aspose.Slides](../../../)