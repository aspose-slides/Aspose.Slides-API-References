---
title: GetFrame()
second_title: Odnośnik API Aspose.Slides dla C++
description: Pobierz bieżącą klatkę PresentationPlayer.
type: docs
weight: 14
url: /pl/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() metoda

Pobierz bieżącą [PresentationPlayer](../../presentationplayer/) klatkę.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Uwagi



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

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../../aspose.slides/iimage/)
* Class [FrameTickEventArgs](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)