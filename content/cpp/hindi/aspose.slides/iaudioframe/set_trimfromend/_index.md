---
title: set_TrimFromEnd()
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: प्लेबैक के दौरान मीडिया के अंत से हटाई जाने वाली समय अवधि को मिलिसेकंड में निर्दिष्ट करता है। लिखें float.
type: docs
weight: 443
url: /hi/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) मेथड


मीडिया के अंत से हटाए जाने वाले समय अवधि को निर्दिष्ट करता है, जो प्लेबैक के दौरान मिलिसेकंड में होता है। लिखें **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// ऑडियो फ़्रेम जोड़ें
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// अंत से ट्रिम करने का समय 2 सेकंड सेट करें
audioFrame->set_TrimFromEnd(2000.0f);
```

## संबंधित देखें

* क्लास [IAudioFrame](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)