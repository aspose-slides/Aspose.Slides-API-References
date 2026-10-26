---
title: Run()
second_title: Aspose.Slides per C++ Riferimento API
description: Esegue la generazione degli eventi di animazione per ogni diapositiva.
type: docs
weight: 92
url: /it/aspose.slides.export/presentationanimationsgenerator/run/
---
## PresentationAnimationsGenerator::Run(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<ISlide\>\>\>) metodo

Esegui la generazione degli eventi di animazione per ogni diapositiva.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::Run(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<ISlide>>> slides)
```

## Osservazioni

```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());
auto player = System::MakeObject<PresentationPlayer>(animationsGenerator, 33);

animationsGenerator->NewAnimation.connect(static_cast<std::function<void(System::SharedPtr<IPresentationAnimationPlayer>)>>(
    [](System::SharedPtr<IPresentationAnimationPlayer> animationPlayer) -> void
{
    // gestisci la nuova animazione
}));

player->FrameTick.connect(static_cast<std::function<void(System::SharedPtr<PresentationPlayer>, System::SharedPtr<FrameTickEventArgs>)>>(
    [](System::SharedPtr<PresentationPlayer> sender, System::SharedPtr<FrameTickEventArgs> args) -> void
{
    // gestisci il tick del fotogramma all'interno della nuova animazione
}));

animationsGenerator->Run(presentation->get_Slides());
```

## PresentationAnimationsGenerator::Run(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<ISlide\>\>\>, int32_t, PresentationPlayer::FrameTickHandler) metodo

Esegui la generazione degli eventi di animazione per ogni diapositiva.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::Run(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<ISlide>>> slides, int32_t fps, PresentationPlayer::FrameTickHandler onFrame)
```

## Osservazioni

```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->Run(presentation->get_Slides(), 33, static_cast<PresentationPlayer::FrameTickHandler>(static_cast<std::function<void(System::SharedPtr<PresentationPlayer>, System::SharedPtr<FrameTickEventArgs>)>>(
    [](System::SharedPtr<PresentationPlayer> sender, System::SharedPtr<FrameTickEventArgs> args) -> void
{
    sender->FrameTick.connect(static_cast<std::function<void(System::SharedPtr<PresentationPlayer>, System::SharedPtr<FrameTickEventArgs>)>>(
        [](System::SharedPtr<PresentationPlayer> sender2, System::SharedPtr<FrameTickEventArgs> args2) -> void
    {
        args2->GetFrame()->Save(System::String::Format(u"frame_{0}.png", sender2->get_FrameIndex()));
    }));
})));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FrameTickHandler](../../presentationplayer/frametickhandler/)
* Classe [IEnumerable](../../../system.collections.generic/ienumerable/)
* Classe [ISlide](../../../aspose.slides/islide/)
* Classe [PresentationAnimationsGenerator](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)