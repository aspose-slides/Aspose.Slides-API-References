---
title: set_HideInk()
second_title: Aspose.Slides für C++ API-Referenz
description: Zeigt Ink-Elemente im exportierten Dokument an oder blendet sie aus.
type: docs
weight: 14
url: /de/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) Methode


Zeigt [Ink](../../../aspose.slides.ink/)-Elemente im exportierten Dokument an oder blendet sie aus.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## Hinweise


Der Standardwert ist false. 

Das folgende Beispiel zeigt, wie [Ink](../../../aspose.slides.ink/)-Elemente im exportierten PDF-Dokument ausgeblendet werden: 
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