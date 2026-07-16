---
title: GetFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la trame actuelle du PresentationPlayer.
type: docs
weight: 14
url: /fr/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() méthode


Obtenez la trame [PresentationPlayer](../../presentationplayer/) actuelle.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Remarques



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

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IImage](../../../aspose.slides/iimage/)
* Classe [FrameTickEventArgs](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)