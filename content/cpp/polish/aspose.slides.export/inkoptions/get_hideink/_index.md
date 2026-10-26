---
title: get_HideInk()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Wyświetla lub ukrywa elementy Ink w wyeksportowanym dokumencie.
type: docs
weight: 1
url: /pl/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() metoda

Pokazuje lub ukrywa [Ink](../../../aspose.slides.ink/) elementy w wyeksportowanym dokumencie.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Uwagi

Domyślna wartość to false. 

Poniższy przykład pokazuje, jak ukryć [Ink](../../../aspose.slides.ink/) elementy w wyeksportowanym dokumencie PDF: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Zobacz także

* Klasa [InkOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)