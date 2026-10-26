---
title: Portion()
second_title: Aspose.Slides for C++ API Referansı
description: "Sunum içinde her bir ForEach::Portion öğesini yinele."
type: docs
weight: 66
url: /tr/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) metot


[Presentation](../../../aspose.slides/presentation/) içinde her bir [ForEach::Portion](./)'yi yineleyin.

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) parçaları yinelemek için |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback her bir portion için çağrılacak |
## Açıklamalar


Portions tüm slayt tiplerinde - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) ve [ForEach::LayoutSlide](../layoutslide/) yineletilecektir.



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) metot


[Presentation](../../../aspose.slides/presentation/) içinde her bir [ForEach::Portion](./)'yi yineleyin.

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) parçaları yinelemek için |
| includeNotes | **bool** | İşleme sırasında NotesSlides'in dahil edilip edilmeyeceğini gösteren bayrak |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | Callback her bir portion için çağrılacak |
## Açıklamalar


Portions tüm slayt tiplerinde - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) ve [NotesSlide](../../../aspose.slides/notesslide/) yineletilecektir.



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)