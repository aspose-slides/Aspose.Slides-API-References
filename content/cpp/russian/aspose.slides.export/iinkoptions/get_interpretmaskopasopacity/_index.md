---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides для C++ справки по API
description: Использует операцию ROP или непрозрачность для отрисовки кисти.
type: docs
weight: 27
url: /ru/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() метод


Использует операцию ROP или непрозрачность для отрисовки кисти.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Замечания


Значение по умолчанию — true. 

Следующий пример демонстрирует, как настроить использование ROP для экспорта элементов [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## См. также

* Класс [IInkOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)