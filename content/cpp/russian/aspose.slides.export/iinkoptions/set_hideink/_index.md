---
title: set_HideInk()
second_title: Aspose.Slides для C++ справочник API
description: Показывает или скрывает элементы Ink в экспортированном документе.
type: docs
weight: 14
url: /ru/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) метод


Показывает или скрывает [Ink](../../../aspose.slides.ink/) элементы в экспортированном документе.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## Примечания


Значение по умолчанию — false. 

Следующий пример демонстрирует, как скрыть [Ink](../../../aspose.slides.ink/) элементы в экспортированном PDF-документе: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## См. также

* Класс [IInkOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)