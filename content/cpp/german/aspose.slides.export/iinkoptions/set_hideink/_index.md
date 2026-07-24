---
title: set_HideInk()
second_title: Aspose.Slides für C++ API-Referenz
description: Zeigt oder verbirgt Ink-Elemente im exportierten Dokument.
type: docs
weight: 14
url: /de/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) Methode

Zeigt oder verbirgt [Ink](../../../aspose.slides.ink/)-Elemente im exportierten Dokument.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## Bemerkungen

Standardwert ist false. 

Das nächste Beispiel zeigt, wie man [Ink](../../../aspose.slides.ink/)-Elemente im exportierten PDF-Dokument ausblendet: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Siehe auch

* Klasse [IInkOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)