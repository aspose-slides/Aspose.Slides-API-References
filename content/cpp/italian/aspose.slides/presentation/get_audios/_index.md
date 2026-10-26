---
title: get_Audios()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce la raccolta di tutti i file audio incorporati nella presentazione. Solo lettura IAudioCollection.
type: docs
weight: 222
url: /it/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() metodo


Restituisce la raccolta di tutti i file audio incorporati nella presentazione. Solo lettura [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Osservazioni


L'esempio seguente mostra come aggiungere un collegamento ipertestuale a un file audio. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioCollection](../../iaudiocollection/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)