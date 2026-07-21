---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides для справочника API C++
description: Определяет, будет ли Aspose.Slides удалять все встроенные двоичные объекты при загрузке презентации.
type: docs
weight: 352
url: /ru/aspose.slides/loadoptions/set_deleteembeddedbinaryobjects/
---
## LoadOptions::set_DeleteEmbeddedBinaryObjects(bool) метод


Определяет, будет ли [Aspose.Slides](../../) удалять все встроенные двоичные объекты при загрузке презентации.

```cpp
void Aspose::Slides::LoadOptions::set_DeleteEmbeddedBinaryObjects(bool value) override
```

## Примечания


Типы встроенных двоичных объектов:

* VBA Project [IPresentation::VbaProject](../)
* OLE Object встроенные данные [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) двоичные данные [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)


Запишите **bool**. 

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