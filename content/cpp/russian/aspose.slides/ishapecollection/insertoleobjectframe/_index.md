---
title: InsertOleObjectFrame()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу.
type: docs
weight: 79
url: /ru/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) метод

Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому вставляется кадр OLE-объекта. |
| x | **float** | Координата x нового кадра OLE в пунктах. |
| y | **float** | Координата y нового кадра OLE в пунктах. |
| width | **float** | Ширина нового кадра OLE в пунктах. |
| height | **float** | Высота нового кадра OLE в пунктах. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Встроенная информация OLE-данных ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Возвращаемое значение

Созданный [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) метод

Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому вставляется кадр OLE-объекта. |
| x | **float** | Координата x нового кадра OLE в пунктах. |
| y | **float** | Координата y нового кадра OLE в пунктах. |
| width | **float** | Ширина нового кадра OLE в пунктах. |
| height | **float** | Высота нового кадра OLE в пунктах. |
| className | [System::String](../../../system/string/) | Имя класса OLE-объекта. |
| path | [System::String](../../../system/string/) | Путь к связанному файлу. |

### Возвращаемое значение

Созданный [IOleObjectFrame](../../ioleobjectframe/).

## Примечания

Этот путь сохраняется в презентации дословно. Если указан относительный путь, файл будет недоступен при открытии презентации из другого каталога.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IOleObjectFrame](../../ioleobjectframe/)
* Класс [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Класс [IShapeCollection](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)