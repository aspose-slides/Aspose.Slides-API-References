---
title: set_IncludeOleData()
second_title: Aspose.Slides pro C++ API Reference
description: True pro převod všech OLE dat z prezentace do vložených souborů ve výsledném PDF. Zapište bool.
type: docs
weight: 469
url: /cs/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) metoda

True pro převod všech OLE dat z prezentace do vložených souborů ve výsledném PDF. Zapište **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
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

* Třída [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)