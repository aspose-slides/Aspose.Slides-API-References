---
title: get_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, будет ли Aspose.Slides удалять все встроенные двоичные объекты при загрузке презентации.
type: docs
weight: 339
url: /ru/aspose.slides/loadoptions/get_deleteembeddedbinaryobjects/
---
## LoadOptions::get_DeleteEmbeddedBinaryObjects() метод

Определяет, будет ли [Aspose.Slides](../../) удалять все встроенные двоичные объекты при загрузке презентации.

```cpp
bool Aspose::Slides::LoadOptions::get_DeleteEmbeddedBinaryObjects() override
```

## Примечания

Типы встроенных двоичных объектов:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object embedded data [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) binary data [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Читать **bool**. 

По умолчанию **false**. 

Следующий пример показывает, как загрузить презентацию без каких-либо встроенных двоичных объектов. 
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## См. также

* Класс [LoadOptions](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)