---
title: InsertAudioFrameLinked()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый аудио-кадр, связанный с внешним аудиофайлом, и вставляет его в коллекцию фигур в указанном индексе.
type: docs
weight: 274
url: /ru/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) метод

Создает новый аудио-кадр, связанный с внешним аудиофайлом, и вставляет его в коллекцию фигур в указанном индексе.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, в котором вставляется аудио-кадр. |
| x | **float** | Координата x нового аудио-кадра в пунктах. |
| y | **float** | Координата y нового аудио-кадра в пунктах. |
| width | **float** | Ширина нового аудио-кадра в пунктах. |
| height | **float** | Высота нового аудио-кадра в пунктах. |
| fname | [System::String](../../../system/string/) | Путь или имя внешнего аудиофайла для ссылки. |

### Возвращаемое значение

Созданный [IAudioFrame](../../iaudioframe/).

## См. также

* Определение типа [SharedPtr](../../../system/sharedptr/)
* Класс [IAudioFrame](../../iaudioframe/)
* Класс [String](../../../system/string/)
* Класс [ShapeCollection](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)