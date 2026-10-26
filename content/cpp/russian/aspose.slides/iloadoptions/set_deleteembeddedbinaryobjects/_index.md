---
title: set_DeleteEmbeddedBinaryObjects()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, будет ли Aspose.Slides удалять все встроенные бинарные объекты при загрузке презентации.
type: docs
weight: 352
url: /ru/aspose.slides/iloadoptions/set_deleteembeddedbinaryobjects/
---
## ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool) метод

Определяет, будет ли [Aspose.Slides](../../) удалять все встроенные бинарные объекты при загрузке презентации.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_DeleteEmbeddedBinaryObjects(bool value)=0
```

## Примечания

Типы встроенных бинарных объектов:

* Проект VBA [IPresentation::VbaProject](../)
* встроенные данные OLE Object [IOleEmbeddedDataInfo::get_EmbeddedFileData](../../ioleembeddeddatainfo/get_embeddedfiledata/)
* ActiveX [Control](../../control/) бинарные данные [IControl::get_ActiveXControlBinary](../../icontrol/get_activexcontrolbinary/)

Запишите **bool**.

По умолчанию **false**.

Следующий пример показывает, как загрузить презентацию без каких-либо встроенных бинарных объектов.
```cpp
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->set_DeleteEmbeddedBinaryObjects(true);

System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.ppt", loadOptions);
pres->Save(u"output_WithoutBinaryObjects.ppt", SaveFormat::Ppt);
```

## См. также

* Класс [ILoadOptions](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)