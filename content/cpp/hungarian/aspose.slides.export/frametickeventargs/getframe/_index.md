---
title: GetFrame()
second_title: Aspose.Slides for C++ API referencia
description: Az aktuális PresentationPlayer keretet lekéri.
type: docs
weight: 14
url: /hu/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() metódus


A jelenlegi [PresentationPlayer](../../presentationplayer/) keretet lekéri.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Megjegyzés



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

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IImage](../../../aspose.slides/iimage/)
* Osztály [FrameTickEventArgs](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)