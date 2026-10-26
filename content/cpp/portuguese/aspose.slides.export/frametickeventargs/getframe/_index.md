---
title: GetFrame()
second_title: Aspose.Slides para C++ Referência da API
description: Obtenha o quadro atual do PresentationPlayer.
type: docs
weight: 14
url: /pt/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() método

Obtenha o [PresentationPlayer](../../presentationplayer/) quadro atual.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Observações

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

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../../aspose.slides/iimage/)
* Classe [FrameTickEventArgs](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)