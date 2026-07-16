---
title: get_FrameIndex()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient l'index de la trame.
type: docs
weight: 1
url: /fr/aspose.slides.export/presentationplayer/get_frameindex/
---
## PresentationPlayer::get_FrameIndex() méthode


Obtient l'index de la trame.

```cpp
int32_t Aspose::Slides::Export::PresentationPlayer::get_FrameIndex()
```

## Remarques



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

## Voir aussi

* Classe [PresentationPlayer](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)