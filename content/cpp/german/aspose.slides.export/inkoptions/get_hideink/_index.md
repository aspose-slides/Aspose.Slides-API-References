---
title: get_HideInk()
second_title: Aspose.Slides für C++ API-Referenz
description: Zeigt Ink-Elemente im exportierten Dokument an oder blendet sie aus.
type: docs
weight: 1
url: /de/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() Methode


Zeigt oder blendet [Ink](../../../aspose.slides.ink/) Elemente im exportierten Dokument aus.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Hinweise


Standardwert ist false. 

Das nächste Beispiel zeigt, wie man [Ink](../../../aspose.slides.ink/) Elemente im exportierten PDF-Dokument ausblendet: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Siehe auch

* Klasse [InkOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)