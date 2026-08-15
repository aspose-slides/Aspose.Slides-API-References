---
title: Run()
second_title: Aspose.Slides for C++ API 參考
description: 為每張投影片執行動畫事件的產生。
type: docs
weight: 92
url: /zh-hant/aspose.slides.export/presentationanimationsgenerator/run/
---
## PresentationAnimationsGenerator::Run(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<ISlide\>\>\>) 方法

為每張投影片執行動畫事件的產生。

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::Run(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<ISlide>>> slides)
```

## 備註

```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());
auto player = System::MakeObject<PresentationPlayer>(animationsGenerator, 33);

animationsGenerator->NewAnimation.connect(static_cast<std::function<void(System::SharedPtr<IPresentationAnimationPlayer>)>>(
    [](System::SharedPtr<IPresentationAnimationPlayer> animationPlayer) -> void
{
    // 處理新動畫
}));

player->FrameTick.connect(static_cast<std::function<void(System::SharedPtr<PresentationPlayer>, System::SharedPtr<FrameTickEventArgs>)>>(
    [](System::SharedPtr<PresentationPlayer> sender, System::SharedPtr<FrameTickEventArgs> args) -> void
{
    // 處理新動畫中的幀滴答
}));

animationsGenerator->Run(presentation->get_Slides());
```

## PresentationAnimationsGenerator::Run(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<ISlide\>\>\>, int32_t, PresentationPlayer::FrameTickHandler) 方法

為每張投影片執行動畫事件的產生。

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::Run(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<ISlide>>> slides, int32_t fps, PresentationPlayer::FrameTickHandler onFrame)
```

## 備註

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

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FrameTickHandler](../../presentationplayer/frametickhandler/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 類別 [ISlide](../../../aspose.slides/islide/)
* 類別 [PresentationAnimationsGenerator](../)
* 命名空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)