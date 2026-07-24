---
title: GetFrame()
second_title: Aspose.Slides für C++ API Referenz
description: Ruft das aktuelle PresentationPlayer-Frame ab.
type: docs
weight: 14
url: /de/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() Methode


Rufen Sie das aktuelle [PresentationPlayer](../../presentationplayer/) Frame ab.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Hinweise



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

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../../aspose.slides/iimage/)
* Klasse [FrameTickEventArgs](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)