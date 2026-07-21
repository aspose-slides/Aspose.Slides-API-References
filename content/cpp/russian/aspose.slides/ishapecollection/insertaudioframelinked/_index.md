---
title: InsertAudioFrameLinked()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый аудио-кадр, связанный с внешним аудиофайлом, и вставляет его в коллекцию фигур по указанному индексу.
type: docs
weight: 235
url: /ru/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) метод

Создает новый аудио-кадр, связанный с внешним аудиофайлом, и вставляет его в коллекцию фигур по указанному индексу.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому следует вставить аудио-кадр. |
| x | **float** | Координата x нового аудио-кадра в пунктах. |
| y | **float** | Координата y нового аудио-кадра в пунктах. |
| width | **float** | Ширина нового аудио-кадра в пунктах. |
| height | **float** | Высота нового аудио-кадра в пунктах. |
| fname | [System::String](../../../system/string/) | Путь или имя внешнего аудиофайла для ссылки. |

### Возвращаемое значение

Созданный [IAudioFrame](../../iaudioframe/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAudioFrame](../../iaudioframe/)
* Класс [String](../../../system/string/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)