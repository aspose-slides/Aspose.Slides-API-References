---
title: set_RewindAudio()
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که آیا یک صدا پس از پخش به‌صورت خودکار به ابتدا بازگردد. مقدار bool را بنویسید.
type: docs
weight: 248
url: /fa/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) متد

تعیین می‌کند که آیا صدا پس از پخش به‌صورت خودکار به ابتدا بازگردد یا نه. مقدار **bool** را بنویسید.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
```

## توضیحات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Add Audio Frame
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```

## مراجع
* کلاس [IAudioFrame](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)