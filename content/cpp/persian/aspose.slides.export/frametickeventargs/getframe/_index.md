---
title: GetFrame()
second_title: Aspose.Slides برای مرجع API C++
description: فریم فعلی PresentationPlayer را دریافت کنید.
type: docs
weight: 14
url: /fa/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() متد


فریم فعلی [PresentationPlayer](../../presentationplayer/) را دریافت کنید.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## توضیحات



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(pres);
auto player = System::MakeObject<PresentationPlayer>(animationsGenerator, 33);

int32_t frameNumber = 0;
player->FrameTick.connect(static_cast<std::function<void(System::SharedPtr<PresentationPlayer>, System::SharedPtr<FrameTickEventArgs>)>>(
    [&frameNumber](System::SharedPtr<PresentationPlayer> sender, System::SharedPtr<FrameTickEventArgs> args) -> void
{
    args->GetFrame()->Save(System::String::Format(u"frame_{0}.png", frameNumber++));
}));

animationsGenerator->Run(pres->get_Slides());
```

## همچنین ببینید

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IImage](../../../aspose.slides/iimage/)
* کلاس [FrameTickEventArgs](../)
* فضای نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)