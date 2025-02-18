---
title: set_VolumeValue()
second_title: Aspose.Slides for C++ API Reference
description: Sets the audio volume in percents. Write float.
type: docs
weight: 391
url: /aspose.slides/iaudioframe/set_volumevalue/
---
## IAudioFrame::set_VolumeValue(float) method


Sets the audio volume in percents. Write **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_VolumeValue(float value)=0
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

* Class [IAudioFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)