---
title: Paragraph()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Presentation에서 각 ForEach::Paragraph를 반복합니다."
type: docs
weight: 53
url: /ko/aspose.slides.lowcode/foreach/paragraph/
---
## ForEach::Paragraph(System::SharedPtr\<Presentation\>, ForEach::ForEachParagraphCallback) 메서드


각 [ForEach::Paragraph](./)을 [Presentation](../../../aspose.slides/presentation/)에서 반복합니다.

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, ForEach::ForEachParagraphCallback forEachParagraph)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 문단을 반복하기 위한 |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | 각 문단에 대해 호출되는 콜백 |
## 비고


모든 종류의 슬라이드에서 도형이 반복됩니다 - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) 및 [ForEach::LayoutSlide](../layoutslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, callback);
```

## ForEach::Paragraph(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachParagraphCallback) 메서드


각 [ForEach::Paragraph](./)을 [Presentation](../../../aspose.slides/presentation/)에서 반복합니다.

```cpp
static void Aspose::Slides::LowCode::ForEach::Paragraph(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachParagraphCallback forEachParagraph)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 문단을 반복하기 위한 |
| includeNotes | **bool** | NotesSlides를 처리에 포함할지 여부를 나타내는 플래그. |
| forEachParagraph | [ForEach::ForEachParagraphCallback](../foreachparagraphcallback/) | 각 문단에 대해 호출되는 콜백 |
## 비고


모든 종류의 슬라이드에서 도형이 반복됩니다 - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) 및 [NotesSlide](../../../aspose.slides/notesslide/)



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", para->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Paragraph(pres, true, callback);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachParagraphCallback](../foreachparagraphcallback/)
* 클래스 [Presentation](../../../aspose.slides/presentation/)
* 클래스 [ForEach](../)
* 네임스페이스 [Aspose::Slides::LowCode](../../)
* 라이브러리 [Aspose.Slides](../../../)