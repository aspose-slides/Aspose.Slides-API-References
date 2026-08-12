---
title: get_Audios()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: प्रस्तुति में सभी एम्बेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य IAudioCollection.
type: docs
weight: 222
url: /hi/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() विधि


प्रस्तुति में सभी एम्बेडेड ऑडियो फ़ाइलों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## टिप्पणियाँ


निम्नलिखित उदाहरण दर्शाते हैं कि ऑडियो फ़ाइल में एक हाइपरलिंक कैसे जोड़ा जाए। 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IAudioCollection](../../iaudiocollection/)
* क्लास [Presentation](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)