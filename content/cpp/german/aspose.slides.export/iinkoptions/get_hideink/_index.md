---
title: get_HideInk()
second_title: Aspose.Slides für C++ API-Referenz
description: Zeigt Ink-Elemente im exportierten Dokument an oder blendet sie aus.
type: docs
weight: 1
url: /de/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() Methode

Zeigt [Ink](../../../aspose.slides.ink/)-Elemente im exportierten Dokument an oder blendet sie aus.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Bemerkungen

Der Standardwert ist false. 

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