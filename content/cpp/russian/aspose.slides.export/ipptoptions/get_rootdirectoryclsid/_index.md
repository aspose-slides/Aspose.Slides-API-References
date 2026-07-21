---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides для C++ справка API
description: Представляет GUID (CLSID) класса объекта, который хранится в записи корневого каталога. Может использоваться для COM-активации приложения документа. Значение по умолчанию — '64818D11-4F9B-11CF-86EA-00AA00B929E8', которое соответствует 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /ru/aspose.slides.export/ipptoptions/get_rootdirectoryclsid/
---
## IPptOptions::get_RootDirectoryClsid() метод


Представляет GUID (CLSID) класса объекта, сохраняемый в записи корневого каталога. Может использоваться для COM-активации приложения документа. Значение по умолчанию — '64818D11-4F9B-11CF-86EA-00AA00B929E8', которое соответствует 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual System::Guid Aspose::Slides::Export::IPptOptions::get_RootDirectoryClsid()=0
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
* Класс [IPptOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)