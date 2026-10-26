---
title: Slide()
second_title: Referensi API Aspose.Slides untuk C++
description: "Iterasi setiap ForEach::Slide dalam Presentasi."
type: docs
weight: 1
url: /id/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) metode


Iterasi setiap [ForEach::Slide](./) dalam [Presentation](../../../aspose.slides/presentation/).

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) untuk mengiterasi slide |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | Callback yang akan dipanggil untuk setiap slide |
## Catatan




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```




## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* Kelas [Presentation](../../../aspose.slides/presentation/)
* Kelas [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Perpustakaan [Aspose.Slides](../../../)