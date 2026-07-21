---
title: set_HideInk()
second_title: Справочник API Aspose.Slides для C++
description: Отображает или скрывает элементы Ink в экспортируемом документе.
type: docs
weight: 14
url: /ru/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) метод


Отображает или скрывает элементы [Ink](../../../aspose.slides.ink/) в экспортируемом документе.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## Примечания


Значение по умолчанию — false. 

Следующий пример демонстрирует, как скрыть элементы [Ink](../../../aspose.slides.ink/) в экспортируемом PDF-документе: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## См. также

* Класс [InkOptions](../)
* Простейство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)