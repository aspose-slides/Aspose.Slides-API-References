---
title: GetFrame()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++ 
description: รับเฟรม PresentationPlayer ปัจจุบัน.
type: docs
weight: 14
url: /th/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() วิธีการ


รับเฟรม [PresentationPlayer](../../presentationplayer/) ปัจจุบัน.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## หมายเหตุ



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

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IImage](../../../aspose.slides/iimage/)
* คลาส [FrameTickEventArgs](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)