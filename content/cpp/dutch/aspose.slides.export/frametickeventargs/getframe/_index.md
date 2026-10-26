---
title: GetFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal het huidige PresentationPlayer-frame op.
type: docs
weight: 14
url: /nl/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() methode


Haal het huidige [PresentationPlayer](../../presentationplayer/) frame.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Opmerkingen



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

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IImage](../../../aspose.slides/iimage/)
* Klasse [FrameTickEventArgs](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)