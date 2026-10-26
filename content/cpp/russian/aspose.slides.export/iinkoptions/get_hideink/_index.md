---
title: get_HideInk()
second_title: Aspose.Slides для C++ справки API
description: Показывает или скрывает элементы Ink в экспортируемом документе.
type: docs
weight: 1
url: /ru/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() метод

Показывает или скрывает [Ink](../../../aspose.slides.ink/) элементы в экспортируемом документе.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Примечания

Значение по умолчанию - false.

Следующий пример показывает, как скрыть [Ink](../../../aspose.slides.ink/) элементы в экспортируемом PDF-документе:
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