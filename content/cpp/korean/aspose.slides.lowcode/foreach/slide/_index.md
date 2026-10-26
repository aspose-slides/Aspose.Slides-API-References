---
title: Slide()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Presentation에서 각 ForEach::Slide를 반복합니다."
type: docs
weight: 1
url: /ko/aspose.slides.lowcode/foreach/slide/
---
## ForEach::Slide(System::SharedPtr\<Presentation\>, ForEach::ForEachSlideCallback) 메서드

[Presentation](../../../aspose.slides/presentation/)에서 [ForEach::Slide](./)를 반복합니다.

```cpp
static void Aspose::Slides::LowCode::ForEach::Slide(System::SharedPtr<Presentation> pres, ForEach::ForEachSlideCallback forEachSlide)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) 슬라이드를 반복하기 위해 |
| forEachSlide | [ForEach::ForEachSlideCallback](../foreachslidecallback/) | 각 슬라이드에 대해 호출될 콜백 |
## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto callback = std::function<void(SharedPtr<Slide> slide, int32_t index)>([](SharedPtr<Slide> slide, int32_t index)
{
    slide->set_Name(String::Format(u"Slide #{0}", index));
});

ForEach::Slide(pres, callback);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ForEachSlideCallback](../foreachslidecallback/)
* 클래스 [Presentation](../../../aspose.slides/presentation/)
* 클래스 [ForEach](../)
* 네임스페이스 [Aspose::Slides::LowCode](../../)
* 라이브러리 [Aspose.Slides](../../../)