---
title: set_HideInk()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zobrazí nebo skryje Ink prvky v exportovaném dokumentu.
type: docs
weight: 14
url: /cs/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) metoda

Zobrazí nebo skryje [Ink](../../../aspose.slides.ink/) prvky v exportovaném dokumentu.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
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

* Třída [IInkOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)