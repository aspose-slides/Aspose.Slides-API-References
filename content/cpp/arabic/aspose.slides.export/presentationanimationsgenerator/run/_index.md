---
title: Run()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة C++
description: تشغيل توليد أحداث الرسوم المتحركة لكل شريحة.
type: docs
weight: 92
url: /ar/aspose.slides.export/presentationanimationsgenerator/run/
---
## PresentationAnimationsGenerator::Run(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<ISlide\>\>\>) method


تشغيل توليد أحداث الرسوم المتحركة لكل شريحة.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::Run(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<ISlide>>> slides)
```

## ملاحظات



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());
auto player = System::MakeObject<PresentationPlayer>(animationsGenerator, 33);

animationsGenerator->NewAnimation.connect(static_cast<std::function<void(System::SharedPtr<IPresentationAnimationPlayer>)>>(
    [](System::SharedPtr<IPresentationAnimationPlayer> animationPlayer) -> void
{
    // معالجة الرسوم المتحركة الجديدة
}));

player->FrameTick.connect(static_cast<std::function<void(System::SharedPtr<PresentationPlayer>, System::SharedPtr<FrameTickEventArgs>)>>(
    [](System::SharedPtr<PresentationPlayer> sender, System::SharedPtr<FrameTickEventArgs> args) -> void
{
    // معالجة إشارة إطار الوقت داخل الرسوم المتحركة الجديدة
}));

animationsGenerator->Run(presentation->get_Slides());
```




## PresentationAnimationsGenerator::Run(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<ISlide\>\>\>, int32_t, PresentationPlayer::FrameTickHandler) method


تشغيل توليد أحداث الرسوم المتحركة لكل شريحة.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::Run(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<ISlide>>> slides, int32_t fps, PresentationPlayer::FrameTickHandler onFrame)
```

## ملاحظات



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
}));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FrameTickHandler](../../presentationplayer/frametickhandler/)
* فئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* فئة [ISlide](../../../aspose.slides/islide/)
* فئة [PresentationAnimationsGenerator](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)