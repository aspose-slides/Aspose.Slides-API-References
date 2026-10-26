---
title: set_RootDirectoryClsid()
second_title: Справочник API Aspose.Slides для C++
description: Представляет GUID (CLSID) класса объекта, который хранится в записи корневого каталога. Может использоваться для COM-активации приложения документа. Значение по умолчанию - '64818D11-4F9B-11CF-86EA-00AA00B929E8', которое соответствует 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 14
url: /ru/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) метод

Представляет GUID (CLSID) класса объекта, который хранится в записи корневого каталога. Может использоваться для COM-активации приложения документа. Значение по умолчанию — '64818D11-4F9B-11CF-86EA-00AA00B929E8', которое соответствует 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
```

## Замечания

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```

## См. также

* Класс [Guid](../../../system/guid/)
* Класс [IPptOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)