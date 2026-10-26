---
title: set_HideInk()
second_title: Aspose.Slides pro C++ API Reference
description: Zobrazuje nebo skrývá Ink prvky v exportovaném dokumentu.
type: docs
weight: 14
url: /cs/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) metoda


Zobrazuje nebo skrývá [Ink](../../../aspose.slides.ink/) prvky v exportovaném dokumentu.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## Poznámky


Výchozí hodnota je false. 

Následující příklad ukazuje, jak skrýt [Ink](../../../aspose.slides.ink/) prvky v exportovaném PDF dokumentu: 
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