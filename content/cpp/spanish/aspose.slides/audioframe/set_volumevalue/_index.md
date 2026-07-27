---
title: set_VolumeValue()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece el volumen de audio en porcentajes. Escriba float.
type: docs
weight: 391
url: /es/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) método


Establece el volumen de audio en porcentajes. Escriba **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## Observaciones


Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Agregar cuadro de audio
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Establecer la duración del fundido inicial a 200 ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [AudioFrame](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)