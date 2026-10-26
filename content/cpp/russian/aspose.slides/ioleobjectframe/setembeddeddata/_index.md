---
title: SetEmbeddedData()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает информацию о встроенных данных OLE.
type: docs
weight: 248
url: /ru/aspose.slides/ioleobjectframe/setembeddeddata/
---
## IOleObjectFrame::SetEmbeddedData(System::SharedPtr\<IOleEmbeddedDataInfo\>) метод

Устанавливает информацию о встраиваемых данных OLE.

```cpp
virtual void Aspose::Slides::IOleObjectFrame::SetEmbeddedData(System::SharedPtr<IOleEmbeddedDataInfo> embeddedData)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| embeddedData | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | Встроенные данные [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/) |
## Примечания

Этот метод изменяет свойства объекта, чтобы отразить новые данные, и устанавливает флаг IsObjectLink в значение false, указывая, что объект OLE встроен.

Следующий пример демонстрирует, как изменить встроенные данные OLE и их тип для существующего объекта [IOleObjectFrame](../)
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<OleObjectFrame> oof = System::AsCast<Aspose::Slides::OleObjectFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
if (oof != nullptr)
{
    System::SharedPtr<IOleEmbeddedDataInfo> newData = System::MakeObject<OleEmbeddedDataInfo>(System::IO::File::ReadAllBytes(u"Picture.png"), u"png");
    oof->SetEmbeddedData(newData);
}
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Класс [IOleObjectFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)