---
title: get_HideInk()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zobrazuje nebo skrývá Ink prvky v exportovaném dokumentu.
type: docs
weight: 1
url: /cs/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() metoda

Zobrazí nebo skryje [Ink](../../../aspose.slides.ink/) prvky v exportovaném dokumentu.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Poznámky

Výchozí hodnota je false. 

Další příklad ukazuje, jak skrýt [Ink](../../../aspose.slides.ink/) prvky v exportovaném PDF dokumentu: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Viz také

* Třída [InkOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)