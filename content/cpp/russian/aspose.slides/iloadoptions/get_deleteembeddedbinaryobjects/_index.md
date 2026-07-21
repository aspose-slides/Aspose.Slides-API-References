---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, будет ли Aspose.Slides удалять все вложенные бинарные объекты при загрузке презентации.
type: docs
weight: 339
url: /ru/aspose.slides/iloadoptions/get_deleteembeddedbinaryobjects/
---
## ILoadOptions::get_DeleteEmbeddedBinaryObjects() метод


Определяет, будет ли [Aspose.Slides](../../) удалять все вложенные бинарные объекты при загрузке презентации.

```cpp
virtual bool Aspose::Slides::ILoadOptions::get_DeleteEmbeddedBinaryObjects()=0
```

## Примечания


Типы вложенных бинарных объектов:

* VBA-проект [IPresentation::VbaProject](../)
* данные встроенного OLE-объекта [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) бинарные данные [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Читать **bool**. 

По умолчанию **false**. 

Следующий пример показывает, как загрузить презентацию без каких-либо вложенных бинарных объектов. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## См. также

* Класс [ILoadOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)