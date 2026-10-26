---
title: AddOleObjectFrame()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый кадр OLE-объекта и добавляет его в конец коллекции фигур.
type: docs
weight: 183
url: /ru/aspose.slides/shapecollection/addoleobjectframe/
---
## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) method


Создаёт новый кадр OLE-объекта и добавляет его в конец коллекции фигур.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового OLE-кадра, в пунктах. |
| y | **float** | Координата y нового OLE-кадра, в пунктах. |
| width | **float** | Ширина нового OLE-кадра, в пунктах. |
| height | **float** | Высота нового OLE-кадра, в пунктах. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Информация о встроенных данных OLE ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Возвращаемое значение

Новосозданный [IOleObjectFrame](../../ioleobjectframe/).

## Примечания



Следующий пример показывает, как добавить OLE-объекты в [Slides](../../) PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>();

// Получаем первый слайд
auto slide = pres->get_Slides()->idx_get(0);
// Загружает файл Excel в поток
System::SharedPtr<System::IO::MemoryStream> mstream = System::MakeObject<System::IO::MemoryStream>();
auto fs = System::MakeObject<System::IO::FileStream>(u"book1.xlsx", System::IO::FileMode::Open, System::IO::FileAccess::Read);

System::ArrayPtr<uint8_t> buf = System::MakeArray<uint8_t>(4096, 0);
while (true)
{
    int32_t bytesRead = fs->Read(buf, 0, buf->get_Length());
    if (bytesRead <= 0)
    {
        break;
    }
    mstream->Write(buf, 0, bytesRead);
}

// Создаёт объект данных для встраивания
auto dataInfo = System::MakeObject<OleEmbeddedDataInfo>(mstream->ToArray(), u"xlsx");
// Добавляет форму Ole Object Frame
auto slideSize = pres->get_SlideSize()->get_Size();
auto oleObjectFrame = slide->get_Shapes()->AddOleObjectFrame(0.0f, 0.0f, slideSize.get_Width(), slideSize.get_Height(), dataInfo);
// Записывает файл PPTX на диск
pres->Save(u"OleEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) method


Создаёт новый кадр OLE-объекта и добавляет его в конец коллекции фигур.

```cpp
System::SharedPtr<IOleObjectFrame> Aspose::Slides::ShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x нового OLE-кадра, в пунктах. |
| y | **float** | Координата y нового OLE-кадра, в пунктах. |
| width | **float** | Ширина нового OLE-кадра, в пунктах. |
| height | **float** | Высота нового OLE-кадра, в пунктах. |
| className | [System::String](../../../system/string/) | Имя класса OLE-объекта. |
| path | [System::String](../../../system/string/) | Путь к связанному файлу. |

### Возвращаемое значение

Новосозданный [IOleObjectFrame](../../ioleobjectframe/).

## Примечания



Этот путь сохраняется дословно в презентации. Если указан относительный путь, файл будет недоступен при открытии презентации из другого каталога.

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IOleObjectFrame](../../ioleobjectframe/)
* Класс [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Класс [ShapeCollection](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)