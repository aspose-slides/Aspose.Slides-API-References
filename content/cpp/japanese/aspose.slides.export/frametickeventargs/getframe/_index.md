---
title: GetFrame()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の PresentationPlayer フレームを取得します。
type: docs
weight: 14
url: /ja/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() メソッド

現在の[PresentationPlayer](../../presentationplayer/)フレームを取得します。

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## 備考

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

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IImage](../../../aspose.slides/iimage/)
* クラス [FrameTickEventArgs](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)