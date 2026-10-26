---
title: SetEmbeddedData()
second_title: Aspose.Slides для C++ — справочник API
description: Устанавливает информацию о встроенных данных OLE.
type: docs
weight: 248
url: /ru/aspose.slides/oleobjectframe/setembeddeddata/
---
## OleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) метод

Устанавливает информацию о встроенных данных OLE.

```cpp
void Aspose::Slides::OleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Встроенные данные [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Примечание

Этот метод изменяет свойства объекта, чтобы отразить новые данные, и устанавливает флаг IsObjectLink в значение false, указывая, что объект OLE встроен. 

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Класс [OleObjectFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)