---
title: get_IncludeOleData()
second_title: Referenční příručka API Aspose.Slides pro C++
description: True pro konverzi všech OLE dat z prezentace do vložených souborů ve výsledném PDF. Čte bool.
type: docs
weight: 456
url: /cs/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() metoda

True pro konverzi všech OLE dat z prezentace do vložených souborů ve výsledném PDF. Čte **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)