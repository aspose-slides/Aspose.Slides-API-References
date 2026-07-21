---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides для C++ справка API
description: Использует операцию ROP или Opacity для отрисовки кисти.
type: docs
weight: 40
url: /ru/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) метод


Использует операцию ROP или Opacity для отрисовки кисти.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## Примечания


Значение по умолчанию — true. 

Следующий пример демонстрирует, как установить использование ROP для экспорта [Ink](../../../aspose.slides.ink/) элементов: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## См. также

* Класс [InkOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)