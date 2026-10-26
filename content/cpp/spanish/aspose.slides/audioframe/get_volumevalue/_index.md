---
title: get_VolumeValue()
second_title: Aspose.Slides para la referencia de la API de C++
description: Devuelve el volumen de audio en porcentajes. Leer float.
type: docs
weight: 378
url: /es/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() método


Devuelve el volumen de audio en porcentajes. Leer **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Agregar marco de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer la duración del fundido inicial a 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [AudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)