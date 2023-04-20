---
title: GetFrame()
second_title: Aspose.Slides for C++ API Reference
description: Get the current PresentationPlayer frame.
type: docs
weight: 14
url: /cpp/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() method


Get the current [PresentationPlayer](../../presentationplayer/) frame.

```cpp
System::SharedPtr<System::Drawing::Bitmap> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Remarks



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




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Bitmap](../../../system.drawing/bitmap/)
* Class [FrameTickEventArgs](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)