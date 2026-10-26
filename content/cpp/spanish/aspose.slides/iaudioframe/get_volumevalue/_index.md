---
title: get_VolumeValue()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el volumen de audio en porcentajes. Lectura float.
type: docs
weight: 378
url: /es/aspose.slides/iaudioframe/get_volumevalue/
---
## IAudioFrame::get_VolumeValue() método

Devuelve el volumen de audio en porcentajes. Lectura **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_VolumeValue()=0
```
## Observaciones

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Añadir cuadro de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer la duración del fundido inicial a 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [IAudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)