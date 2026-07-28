---
title: get_Audios()
second_title: Aspose.Slides a C++ API referenciája
description: Visszaadja a prezentációban beágyazott összes hangfájl gyűjteményét. Csak olvasható IAudioCollection.
type: docs
weight: 222
url: /hu/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() metódus

Visszaadja a prezentációban beágyazott összes hangfájl gyűjteményét. Csak olvasható [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Megjegyzések

Az alábbi példák bemutatják, hogyan lehet egy hangfájlhoz hiperhivatkozást hozzáadni.
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudioCollection](../../iaudiocollection/)
* Osztály [Presentation](../)
* névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)