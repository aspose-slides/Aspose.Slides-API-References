---
title: get_HideInk()
second_title: Aspose.Slides для C++ справочник API
description: Показывает или скрывает элементы Ink в экспортированном документе.
type: docs
weight: 1
url: /ru/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() метод


Показывает или скрывает [Ink](../../../aspose.slides.ink/) элементы в экспортированном документе.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Примечания


Значение по умолчанию — false. 

Следующий пример показывает, как скрыть [Ink](../../../aspose.slides.ink/) элементы в экспортированном PDF документе: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## См. также

* Класс [InkOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)