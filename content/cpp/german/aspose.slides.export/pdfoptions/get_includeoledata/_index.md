---
title: get_IncludeOleData()
second_title: Aspose.Slides für C++ API-Referenz
description: True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien in der resultierenden PDF zu konvertieren. Lesen bool.
type: docs
weight: 456
url: /de/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() Methode

True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien in der resultierenden PDF zu konvertieren. Lesen **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Bemerkungen

Standard ist **false**. 

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Siehe auch

* Klasse [PdfOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)