---
title: get_FrameIndex()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce l'indice del fotogramma.
type: docs
weight: 1
url: /it/aspose.slides.export/presentationplayer/get_frameindex/
---
## PresentationPlayer::get_FrameIndex() metodo

Restituisce l'indice del fotogramma.

```cpp
int32_t Aspose::Slides::Export::PresentationPlayer::get_FrameIndex()
```

## Osservazioni



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(pres);
auto player = System::MakeObject<PresentationPlayer>(animationsGenerator, 33);

player->FrameTick.connect(static_cast<std::function<void(System::SharedPtr<PresentationPlayer>, System::SharedPtr<FrameTickEventArgs>)>>(
    [](System::SharedPtr<PresentationPlayer> sender, System::SharedPtr<FrameTickEventArgs> args) -> void
{
    args->GetFrame()->Save(System::String::Format(u"frame_{0}.png", sender->get_FrameIndex()));
}));

animationsGenerator->Run(pres->get_Slides());
```

## Vedi anche

* Classe [PresentationPlayer](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)