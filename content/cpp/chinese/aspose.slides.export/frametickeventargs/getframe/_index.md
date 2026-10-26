---
title: GetFrame()
second_title: Aspose.Slides for C++ API 参考
description: 获取当前的 PresentationPlayer 帧。
type: docs
weight: 14
url: /zh/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() 方法

获取当前 [PresentationPlayer](../../presentationplayer/) 帧。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## 备注

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

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../../aspose.slides/iimage/)
* Class [FrameTickEventArgs](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)