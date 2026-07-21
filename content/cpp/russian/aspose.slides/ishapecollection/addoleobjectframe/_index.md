---
title: AddOleObjectFrame()
second_title: Справочник API Aspose.Slides для C++
description: Создает новый фрейм OLE-объекта и добавляет его в конец коллекции фигур.
type: docs
weight: 66
url: /ru/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) метод

Создает новый фрейм OLE-объекта и добавляет его в конец коллекции фигур.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового фрейма OLE, в пунктах. |
| y | **float** | Координата y нового фрейма OLE, в пунктах. |
| width | **float** | Ширина нового фрейма OLE, в пунктах. |
| height | **float** | Высота нового фрейма OLE, в пунктах. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Информация о встраиваемых данных OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Возвращаемое значение

Созданный [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) метод

Создает новый фрейм OLE-объекта и добавляет его в конец коллекции фигур.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового фрейма OLE, в пунктах. |
| y | **float** | Координата y нового фрейма OLE, в пунктах. |
| width | **float** | Ширина нового фрейма OLE, в пунктах. |
| height | **float** | Высота нового фрейма OLE, в пунктах. |
| className | [System::String](../../../system/string/) | Имя класса OLE-объекта. |
| path | [System::String](../../../system/string/) | Путь к связанному файлу. |

### Возвращаемое значение

Созданный недавно [IOleObjectFrame](../../ioleobjectframe/).

## Примечания

Этот путь сохраняется дословно в презентации. Если указан относительный путь, файл будет недоступен при открытии презентации из другой директории.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IOleObjectFrame](../../ioleobjectframe/)
* Класс [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Класс [IShapeCollection](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)