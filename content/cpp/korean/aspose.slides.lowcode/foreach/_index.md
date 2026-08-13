---
title: ForEach
second_title: Aspose.Slides C++ API 참조
description: 다양한 Presentation 모델 객체를 반복하도록 설계된 메서드 그룹을 나타냅니다. 이러한 메서드는 Presentation 요소의 서식이나 내용을 반복해서 변경해야 할 때, 예를 들어 각 부분의 서식을 변경하는 경우에 유용합니다.
type: docs
weight: 40
url: /ko/aspose.slides.lowcode/foreach/
---
## ForEach 클래스


다양한 [Presentation](../../aspose.slides/presentation/) 모델 객체를 반복하도록 설계된 메서드 그룹을 나타냅니다. 이러한 메서드는 [Presentation](../../aspose.slides/presentation/)' 요소의 서식이나 내용을 반복해서 변경해야 할 때, 예를 들어 각 부분의 서식을 변경하는 경우에 유용합니다.

```cpp
class ForEach
```

## 메서드

| Method | Description |
| --- | --- |
|  [ForEach](./foreach/)() |  |
| static void [LayoutSlide](./layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachLayoutSlideCallback](./foreachlayoutslidecallback/)) | 각 [ForEach::LayoutSlide](./layoutslide/)를 [Presentation](../../aspose.slides/presentation/)에서 순회합니다. |
| static void [MasterSlide](./masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachMasterSlideCallback](./foreachmasterslidecallback/)) | 각 [ForEach::MasterSlide](./masterslide/)를 [Presentation](../../aspose.slides/presentation/)에서 순회합니다. |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | 각 [ForEach::Paragraph](./paragraph/)를 [Presentation](../../aspose.slides/presentation/)에서 순회합니다. |
| static void [Paragraph](./paragraph/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachParagraphCallback](./foreachparagraphcallback/)) | 각 [ForEach::Paragraph](./paragraph/)를 [Presentation](../../aspose.slides/presentation/)에서 순회합니다. |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | 각 [ForEach::Portion](./portion/)를 [Presentation](../../aspose.slides/presentation/)에서 순회합니다. |
| static void [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachPortionCallback](./foreachportioncallback/)) | 각 [ForEach::Portion](./portion/)를 [Presentation](../../aspose.slides/presentation/)에서 순회합니다. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | 각 [ForEach::Shape](./shape/)를 [Presentation](../../aspose.slides/presentation/)에서 순회합니다. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, **bool**, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | 각 [ForEach::Shape](./shape/)를 [Presentation](../../aspose.slides/presentation/)에서 순회합니다. |
| static void [Shape](./shape/)([System::SharedPtr](../../system/sharedptr/)\<[BaseSlide](../../aspose.slides/baseslide/)\>, [ForEach::ForEachShapeCallback](./foreachshapecallback/)) | 각 [ForEach::Shape](./shape/)를 [BaseSlide](../../aspose.slides/baseslide/)에서 순회합니다. |
| static void [Slide](./slide/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [ForEach::ForEachSlideCallback](./foreachslidecallback/)) | 각 [ForEach::Slide](./slide/)를 [Presentation](../../aspose.slides/presentation/)에서 순회합니다. |

## 타입 정의

| Typedef | Description |
| --- | --- |
| [ForEachSlideCallback](./foreachslidecallback/) | 각 [ForEach::Slide](./slide/)에 대해 [Presentation](../../aspose.slides/presentation/)에서 호출되는 콜백. |
| [ForEachMasterSlideCallback](./foreachmasterslidecallback/) | 각 [ForEach::MasterSlide](./masterslide/)에 대해 [Presentation](../../aspose.slides/presentation/)에서 호출되는 콜백. |
| [ForEachLayoutSlideCallback](./foreachlayoutslidecallback/) | 각 [ForEach::LayoutSlide](./layoutslide/)에 대해 [Presentation](../../aspose.slides/presentation/)에서 호출되는 콜백. |
| [ForEachShapeCallback](./foreachshapecallback/) | 각 [ForEach::Shape](./shape/)에 대해 [Presentation](../../aspose.slides/presentation/)에서 호출되는 콜백. |
| [ForEachParagraphCallback](./foreachparagraphcallback/) | 각 [ForEach::Paragraph](./paragraph/)에 대해 [BaseSlide](../../aspose.slides/baseslide/)에서 호출되는 콜백. |
| [ForEachPortionCallback](./foreachportioncallback/) | 각 [ForEach::Portion](./portion/)에 대해 [ForEach::Paragraph](./paragraph/)에서 [BaseSlide](../../aspose.slides/baseslide/)에 호출되는 콜백. |

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");

auto lambda = [](SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index) -> void
{
    portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"Times New Roman"));
};
auto callback = std::function<void(SharedPtr<Portion> portion, SharedPtr<Paragraph> para, SharedPtr<BaseSlide> slide, int32_t index)>(lambda);

ForEach::Portion(presentation, callback);

presentation->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## 관련 항목

* 네임스페이스 [Aspose::Slides::LowCode](../)
* 라이브러리 [Aspose.Slides](../../)