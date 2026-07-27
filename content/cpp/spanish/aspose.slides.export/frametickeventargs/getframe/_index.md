---
title: GetFrame()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtenga el cuadro actual de PresentationPlayer.
type: docs
weight: 14
url: /es/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() método


Obtenga el cuadro [PresentationPlayer](../../presentationplayer/) actual.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Observaciones



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

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IImage](../../../aspose.slides/iimage/)
* Clase [FrameTickEventArgs](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)