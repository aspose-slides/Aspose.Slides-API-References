---
title: get_Audios()
second_title: Aspose.Slides for C++ API Referansı
description: Sunumda bulunan tüm gömülü ses dosyalarının koleksiyonunu döndürür. Salt okunur IAudioCollection.
type: docs
weight: 222
url: /tr/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() metot

Sunumda yer alan tüm gömülü ses dosyalarının koleksiyonunu döndürür. Salt okunur [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Açıklamalar

Aşağıdaki örnekler, bir ses dosyasına nasıl bir köprü eklenir gösterir. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## İlgili

* Tür Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IAudioCollection](../../iaudiocollection/)
* Sınıf [Presentation](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)