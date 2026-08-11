---
title: GetFrame()
second_title: مرجع API Aspose.Slides للـ C++
description: احصل على إطار PresentationPlayer الحالي.
type: docs
weight: 14
url: /ar/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() طريقة

احصل على [PresentationPlayer](../../presentationplayer/) الإطار الحالي.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## ملاحظات

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

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IImage](../../../aspose.slides/iimage/)
* فئة [FrameTickEventArgs](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)