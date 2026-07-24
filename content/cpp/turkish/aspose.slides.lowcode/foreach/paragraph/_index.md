---
title: Paragraph()
second_title: Aspose.Slides for C++ API Referansı
description: "Presentation içinde her ForEach::Paragraph öğesini yineleyin."
type: docs
weight: 53
url: /tr/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) method

Her bir [ForEach::Paragraph](./) öğesini [Presentation](../../../aspose.slides/presentation/) içinde yineleyin.

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) paragrafları yinelemek için |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | Her paragraf için çağrılacak geri arama |
## Açıklamalar

Şekiller tüm slayt türlerinde yineleyecektir - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) ve [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, callback);
```

## ForEach::Paragraph(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachParagraphCallback) method

Her bir [ForEach::Paragraph](./) öğesini [Presentation](../../../aspose.slides/presentation/) içinde yineleyin.

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) paragrafları yinelemek için |
| includeNotes | **bool** | İşlem sırasında NotSlaytlarının dahil edilip edilmeyeceğini belirten işaret. |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | Her paragraf için çağrılacak geri arama |
## Açıklamalar

Şekiller tüm slayt türlerinde yineleyecektir - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) ve [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Tip Tanımı [ForEachParagraphCallback](../foreachparagraphcallback/)
* Sınıf [Presentation](../../../aspose.slides/presentation/)
* Sınıf [ForEach](../)
* Ad Alanı [Aspose::Slides::LowCode](../../)
* Kütüphane [Aspose.Slides](../../../)