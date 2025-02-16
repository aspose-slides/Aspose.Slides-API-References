---
title: get_VolumeValue()
second_title: Aspose.Slides for C++ API Reference
description: Returns the audio volume in percents. Read float.
type: docs
weight: 378
url: /aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() method


Returns the audio volume in percents. Read **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Add Audio Frame
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## See Also

* Class [AudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)