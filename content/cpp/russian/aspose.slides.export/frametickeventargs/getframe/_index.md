---
title: GetFrame()
second_title: Справочник API Aspose.Slides для C++
description: Получить текущий кадр PresentationPlayer.
type: docs
weight: 14
url: /ru/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() метод


Получить текущий [PresentationPlayer](../../presentationplayer/) кадр.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Примечания


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

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IImage](../../../aspose.slides/iimage/)
* Класс [FrameTickEventArgs](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)