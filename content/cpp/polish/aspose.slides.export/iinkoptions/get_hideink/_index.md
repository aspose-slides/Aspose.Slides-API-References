---
title: get_HideInk()
second_title: Aspose.Slides dla C++ – referencja API
description: Wyświetla lub ukrywa elementy Ink w wyeksportowanym dokumencie.
type: docs
weight: 1
url: /pl/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() metoda


Wyświetla lub ukrywa elementy [Ink](../../../aspose.slides.ink/) w wyeksportowanym dokumencie.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Uwagi


Domyślna wartość to false. 

Następny przykład pokazuje, jak ukryć elementy [Ink](../../../aspose.slides.ink/) w wyeksportowanym dokumencie PDF: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Zobacz również

* Klasa [IInkOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)