---
title: AddAudioFrameEmbedded()
second_title: Справочник API Aspose.Slides для C++
description: "Создаёт новый аудио-кадр с встроенным WAV-файлом и добавляет его в конец коллекции фигур. Встроенное аудио добавляется в коллекцию Presentation::get_Audios."
type: docs
weight: 287
url: /ru/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method

Создает новый аудио-кадр с вложенным WAV-файлом и добавляет его в конец коллекции фигур. Встроенное аудио добавляется в коллекцию [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового аудио-кадра в пунктах. |
| y | **float** | Координата y нового аудио-кадра в пунктах. |
| width | **float** | Ширина нового аудио-кадра в пунктах. |
| height | **float** | Высота нового аудио-кадра в пунктах. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Входной поток, содержащий WAV-данные аудио для встраивания. |

### Возвращаемое значение

Созданный [IAudioFrame](../../iaudioframe/).

## Примечания

Следующий пример показывает, как создать [Audio](../../audio/) Frame.  
```cpp
// Создаёт объект класса презентации, представляющий файл презентации
auto pres = System::MakeObject<Presentation>();

// Получает первый слайд
auto slide = pres->get_Slides()->idx_get(0);
// Загружает wav-файл звука в поток
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Добавляет аудио-кадр
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Устанавливает режим воспроизведения и громкость аудио
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// Записывает файл PowerPoint на диск
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) method

Создает новый аудио-кадр и добавляет его в конец коллекции фигур, используя существующий объект аудио из списка [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового аудио-кадра в пунктах. |
| y | **float** | Координата y нового аудио-кадра в пунктах. |
| width | **float** | Ширина нового аудио-кадра в пунктах. |
| height | **float** | Высота нового аудио-кадра в пунктах. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Экземпляр [IAudio](../../iaudio/) из коллекции [Presentation::get_Audios](../../presentation/get_audios/). |

### Возвращаемое значение

Созданный [IAudioFrame](../../iaudioframe/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAudioFrame](../../iaudioframe/)
* Класс [Stream](../../../system.io/stream/)
* Класс [ShapeCollection](../)
* Класс [IAudio](../../iaudio/)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)