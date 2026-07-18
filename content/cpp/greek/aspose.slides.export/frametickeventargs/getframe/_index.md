---
title: GetFrame()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Λάβετε το τρέχον καρέ του PresentationPlayer.
type: docs
weight: 14
url: /el/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() μέθοδος


Λάβετε το τρέχον [PresentationPlayer](../../presentationplayer/) καρέ.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## Παρατηρήσεις



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

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IImage](../../../aspose.slides/iimage/)
* Κλάση [FrameTickEventArgs](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)