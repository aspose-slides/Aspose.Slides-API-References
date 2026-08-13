---
title: GetFrame()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 PresentationPlayer 프레임을 가져옵니다.
type: docs
weight: 14
url: /ko/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() 메서드


현재 [PresentationPlayer](../../presentationplayer/) 프레임을 가져옵니다.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## 비고



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

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IImage](../../../aspose.slides/iimage/)
* 클래스 [FrameTickEventArgs](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)