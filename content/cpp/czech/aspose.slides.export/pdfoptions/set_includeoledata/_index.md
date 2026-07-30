---
title: set_IncludeOleData()
second_title: Aspose.Slides pro C++ API Reference
description: True k převodu všech OLE dat z prezentace na vložené soubory v výsledném PDF. Zapište bool.
type: docs
weight: 469
url: /cs/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) metoda


True k převodu všech OLE dat z prezentace na vložené soubory v výsledném PDF. Zapište **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
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