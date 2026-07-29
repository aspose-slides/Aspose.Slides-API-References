---
title: GetFrame()
second_title: Aspose.Slides för C++ API-referens
description: Hämta den aktuella PresentationPlayer-ramen.
type: docs
weight: 14
url: /sv/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() metod

Hämta den aktuella [PresentationPlayer](../../presentationplayer/) ram.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Anmärkningar

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

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IImage](../../../aspose.slides/iimage/)
* Klass [FrameTickEventArgs](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)