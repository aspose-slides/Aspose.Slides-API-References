---
title: get_Audios()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna a coleção de todos os arquivos de áudio incorporados na apresentação. Somente leitura IAudioCollection.
type: docs
weight: 222
url: /pt/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() método


Retorna a coleção de todos os arquivos de áudio incorporados na apresentação. Somente leitura [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Observações


O exemplo a seguir mostra como adicionar um hyperlink a um arquivo de áudio. 
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioCollection](../../iaudiocollection/)
* Classe [Presentation](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)