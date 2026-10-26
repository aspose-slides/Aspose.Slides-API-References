---
title: set_HideInk()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Wyświetla lub ukrywa elementy Ink w wyeksportowanym dokumencie.
type: docs
weight: 14
url: /pl/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) metoda

Wyświetla lub ukrywa [Ink](../../../aspose.slides.ink/) elementy w wyeksportowanym dokumencie.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## Uwagi

Domyślna wartość to false. 

Kolejny przykład pokazuje, jak ukryć [Ink](../../../aspose.slides.ink/) elementy w wyeksportowanym dokumencie PDF: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Zobacz także

* Klasa [IInkOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)