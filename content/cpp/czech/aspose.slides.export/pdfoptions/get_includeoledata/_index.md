---
title: get_IncludeOleData()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: True pro převod všech OLE dat z prezentace do vložených souborů ve výsledném PDF. Číst bool.
type: docs
weight: 456
url: /cs/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() metoda


True pro převod všech OLE dat z prezentace do vložených souborů ve výsledném PDF. Číst **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Poznámky


Výchozí hodnota je **false**. 

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Viz také

* Třída [PdfOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)