---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides для C++ справка API
description: Использует операцию ROP или непрозрачность для отрисовки кисти.
type: docs
weight: 27
url: /ru/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() метод


Использует операцию ROP или непрозрачность для отрисовки кисти.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## Примечания


Значение по умолчанию — true. 

Следующий пример демонстрирует, как установить использование ROP для экспорта элементов [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Смотрите также

* Класс [InkOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)