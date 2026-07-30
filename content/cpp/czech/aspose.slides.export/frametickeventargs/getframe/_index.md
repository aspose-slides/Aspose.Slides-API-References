---
title: GetFrame()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá aktuální rámec PresentationPlayeru.
type: docs
weight: 14
url: /cs/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() metoda


Získá aktuální [PresentationPlayer](../../presentationplayer/) rámec.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Poznámky



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

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IImage](../../../aspose.slides/iimage/)
* Třída [FrameTickEventArgs](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)