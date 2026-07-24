---
title: get_FrameIndex()
second_title: Aspose.Slides for C++ API Referansı
description: Kare indeksini alır.
type: docs
weight: 1
url: /tr/aspose.slides.export/presentationplayer/get_frameindex/
---
## PresentationPlayer::get_FrameIndex() metodu


Kare indeksini alır.

```cpp
int32_t Aspose::Slides::Export::PresentationPlayer::get_FrameIndex()
```

## Açıklamalar



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

## Ayrıca Bakınız

* Sınıf [PresentationPlayer](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)