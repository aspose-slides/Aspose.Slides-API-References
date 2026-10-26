---
title: get_IncludeOleData()
second_title: Aspose.Slides dla C++ – odniesienie API
description: True, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF. Odczyt bool.
type: docs
weight: 456
url: /pl/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() metoda

True, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF. Odczyt **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Uwagi

Default is **false**. 

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Zobacz także

* Klasa [PdfOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)