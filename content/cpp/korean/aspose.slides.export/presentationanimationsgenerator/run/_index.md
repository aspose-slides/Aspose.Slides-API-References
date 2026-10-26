---
title: Run()
second_title: Aspose.Slides C++용 API 참조
description: 각 슬라이드에 대한 애니메이션 이벤트 생성을 실행합니다.
type: docs
weight: 92
url: /ko/aspose.slides.export/presentationanimationsgenerator/run/
---
## PresentationAnimationsGenerator::Run(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<ISlide\>\>\>) 메서드

각 슬라이드에 대한 애니메이션 이벤트 생성을 실행합니다.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::Run(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<ISlide>>> slides)
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());
auto player = System::MakeObject<PresentationPlayer>(animationsGenerator, 33);

animationsGenerator->NewAnimation.connect(static_cast<std::function<void(System::SharedPtr<IPresentationAnimationPlayer>)>>(
    [](System::SharedPtr<IPresentationAnimationPlayer> animationPlayer) -> void
{
    // 새 애니메이션 처리
}));

player->FrameTick.connect(static_cast<std::function<void(System::SharedPtr<PresentationPlayer>, System::SharedPtr<FrameTickEventArgs>)>>(
    [](System::SharedPtr<PresentationPlayer> sender, System::SharedPtr<FrameTickEventArgs> args) -> void
{
    // 새 애니메이션 내에서 프레임 틱 처리
}));

animationsGenerator->Run(presentation->get_Slides());
```




## PresentationAnimationsGenerator::Run(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<ISlide\>\>\>, int32_t, PresentationPlayer::FrameTickHandler) 메서드

각 슬라이드에 대한 애니메이션 이벤트 생성을 실행합니다.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::Run(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<ISlide>>> slides, int32_t fps, PresentationPlayer::FrameTickHandler onFrame)
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->Run(presentation->get_Slides(), 33, static_cast<PresentationPlayer::FrameTickHandler>(static_cast<std::function<void(System::SharedPtr<PresentationPlayer>, System::SharedPtr<FrameTickEventArgs>)>>(
    [](System::SharedPtr<PresentationPlayer> sender, System::SharedPtr<FrameTickEventArgs> args) -> void
{
    sender->FrameTick.connect(static_cast<std::function<void(System::SharedPtr<PresentationPlayer>, System::SharedPtr<FrameTickEventArgs>)>>(
        [](System::SharedPtr<PresentationPlayer> sender2, System::SharedPtr<FrameTickEventArgs> args2) -> void
    {
        args2->GetFrame()->Save(System::String::Format(u"frame_{0}.png", sender2->get_FrameIndex()));
    }));
})));
```

## 관련 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 타입 정의 [FrameTickHandler](../../presentationplayer/frametickhandler/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 클래스 [ISlide](../../../aspose.slides/islide/)
* 클래스 [PresentationAnimationsGenerator](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)