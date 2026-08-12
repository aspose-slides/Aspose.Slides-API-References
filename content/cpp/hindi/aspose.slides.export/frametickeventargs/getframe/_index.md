---
title: GetFrame()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान PresentationPlayer फ़्रेम प्राप्त करें।
type: docs
weight: 14
url: /hi/aspose.slides.export/frametickeventargs/getframe/
---
## FrameTickEventArgs::GetFrame() विधि


वर्तमान [PresentationPlayer](../../presentationplayer/) फ़्रेम प्राप्त करें।

```cpp
System::SharedPtr<IImage> Aspose::Slides::Export::FrameTickEventArgs::GetFrame()
```

## टिप्पणियाँ



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

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IImage](../../../aspose.slides/iimage/)
* क्लास [FrameTickEventArgs](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)