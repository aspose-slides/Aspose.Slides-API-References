---
title: get_Audios()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la colección de todos los archivos de audio incrustados en la presentación. Sólo lectura IAudioCollection.
type: docs
weight: 222
url: /es/aspose.slides/presentation/get_audios/
---
## Presentation::get_Audios() método

Devuelve la colección de todos los archivos de audio incrustados en la presentación. Solo lectura [IAudioCollection](../../iaudiocollection/).

```cpp
System::SharedPtr<IAudioCollection> Aspose::Slides::Presentation::get_Audios() override
```

## Observaciones

Los siguientes ejemplos demuestran cómo agregar un hipervínculo a un archivo de audio.
```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"audio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(10.0f, 10.0f, 100.0f, 100.0f, audio);
audioFrame->set_HyperlinkClick(System::MakeObject<Hyperlink>(u"https://www.aspose.com/"));
audioFrame->get_HyperlinkClick()->set_Tooltip(u"More than 70% Fortune 100 companies trust Aspose APIs");
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IAudioCollection](../../iaudiocollection/)
* Clase [Presentation](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)