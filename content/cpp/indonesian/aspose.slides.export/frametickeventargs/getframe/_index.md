---
title: GetFrame()
second_title: Referensi API Aspose.Slides untuk C++
description: Dapatkan frame PresentationPlayer saat ini.
type: docs
weight: 14
url: /id/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() method


Dapatkan frame [PresentationPlayer](../../presentationplayer/) saat ini.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Keterangan


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

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IImage](../../../aspose.slides/iimage/)
* Kelas [FrameTickEventArgs](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)