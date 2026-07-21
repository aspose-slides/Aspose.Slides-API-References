---
title: InsertOleObjectFrame()
second_title: Aspose.Slides для C++ справочника API
description: Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу.
type: docs
weight: 196
url: /ru/aspose.slides/shapecollection/insertoleobjectframe/
---
## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) метод


Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой-базовый индекс, в который будет вставлен кадр OLE-объекта. |
| x | **float** | Координата x нового кадра OLE, в пунктах. |
| y | **float** | Координата y нового кадра OLE, в пунктах. |
| width | **float** | Ширина нового кадра OLE, в пунктах. |
| height | **float** | Высота нового кадра OLE, в пунктах. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Информация о встроенных данных OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Возвращаемое значение

Недавно созданный [IOleObjectFrame](../../ioleobjectframe/).

## Примечания



Этот пример демонстрирует вставку OLE-объекта во второй позиции: 
```cpp
ArrayPtr<uint8_t> fileData = IO::File::ReadAllBytes(u"test.zip");
auto dataInfo = MakeObject<OleEmbeddedDataInfo>(fileData, u"zip");
auto oleObjectFrame = slide->get_Shapes()->InsertOleObjectFrame(2, 150.0f, 20.0f, 50.0f, 50.0f, dataInfo);
```

## ShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) метод


Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой-базовый индекс, в который будет вставлен кадр OLE-объекта. |
| x | **float** | Координата x нового кадра OLE, в пунктах. |
| y | **float** | Координата y нового кадра OLE, в пунктах. |
| width | **float** | Ширина нового кадра OLE, в пунктах. |
| height | **float** | Высота нового кадра OLE, в пунктах. |
| className | [System::String](../../../system/string/) | Имя класса OLE-объекта. |
| path | [System::String](../../../system/string/) | Путь к связанному файлу. |

### Возвращаемое значение

Недавно созданный кадр OLE-объекта.

## Примечания



Этот путь сохраняется без изменений в презентации. Если указан относительный путь, файл будет недоступен при открытии презентации из другого каталога.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IOleObjectFrame](../../ioleobjectframe/)
* Класс [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Класс [ShapeCollection](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)