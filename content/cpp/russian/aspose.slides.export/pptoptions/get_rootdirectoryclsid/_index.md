---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides для C++ справочник API
description: Представляет GUID (CLSID) класса объекта, хранящийся в записи корневого каталога. Может использоваться для COM-активации приложения документа. Значение по умолчанию — '64818D11-4F9B-11CF-86EA-00AA00B929E8', которое соответствует 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /ru/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() метод


Представляет GUID (CLSID) класса объекта, хранящийся в записи корневого каталога. Может использоваться для COM-активации приложения документа. Значение по умолчанию - '64818D11-4F9B-11CF-86EA-00AA00B929E8', которое соответствует 'Microsoft Powerpoint.Slide.8'.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
```

## Примечания



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## См. также

* Класс [Guid](../../../system/guid/)
* Класс [PptOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)