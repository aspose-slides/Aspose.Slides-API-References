---
title: Portion()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Presentation에서 각 ForEach::Portion을 반복합니다."
type: docs
weight: 66
url: /ko/aspose.slides.lowcode/foreach/portion/
---
## ForEach::Portion(System::SharedPtr\<Presentation\>, ForEach::ForEachPortionCallback) 메서드


[Presentation](../../../aspose.slides/presentation/)에서 [ForEach::Portion](./)를 반복합니다.

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, ForEach::ForEachPortionCallback forEachPortion)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 포션을 반복하기 위한 [Presentation](../../../aspose.slides/presentation/) |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | 각 포션에 대해 호출되는 콜백 |
## 비고


포션은 모든 유형의 슬라이드에서 반복됩니다 - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/) 및 [ForEach::LayoutSlide](../layoutslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, callback);
```

## ForEach::Portion(System::SharedPtr\<Presentation\>, bool, ForEach::ForEachPortionCallback) 메서드


[Presentation](../../../aspose.slides/presentation/)에서 [ForEach::Portion](./)를 반복합니다.

```cpp
static void Aspose::Slides::LowCode::ForEach::Portion(System::SharedPtr<Presentation> pres, bool includeNotes, ForEach::ForEachPortionCallback forEachPortion)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 포션을 반복하기 위한 [Presentation](../../../aspose.slides/presentation/) |
| includeNotes | **bool** | 처리 시 NotesSlides를 포함할지 여부를 나타내는 플래그. |
| forEachPortion | [ForEach::ForEachPortionCallback](../foreachportioncallback/) | 각 포션에 대해 호출되는 콜백 |
## 비고


포션은 모든 유형의 슬라이드에서 반복됩니다 - [ForEach::Slide](../slide/), [ForEach::MasterSlide](../masterslide/), [ForEach::LayoutSlide](../layoutslide/) 및 [NotesSlide](../../../aspose.slides/notesslide/)

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)
{
    System::Console::WriteLine(u"{0}, index: {1}", portion->get_Text(), index);
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(pres, true, callback);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachPortionCallback](../foreachportioncallback/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [ForEach](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)