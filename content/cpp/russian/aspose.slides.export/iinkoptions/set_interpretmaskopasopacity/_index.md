---
title: set_InterpretMaskOpAsOpacity()
second_title: Справочник API Aspose.Slides для C++
description: Использует операцию ROP или непрозрачность для отрисовки кисти.
type: docs
weight: 40
url: /ru/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) метод

Использует операцию ROP или непрозрачность для отрисовки кисти.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
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

* Класс [IInkOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)