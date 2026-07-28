---
title: set_IncludeOleData()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Ustaw na true, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF. Zapisz bool.
type: docs
weight: 469
url: /pl/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) metoda

Ustaw na true, aby przekonwertować wszystkie dane OLE z prezentacji na osadzone pliki w wynikowym PDF. Zapisz **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## Uwagi

Domyślnie jest **false**. 

Przykład: 
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