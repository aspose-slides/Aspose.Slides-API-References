---
title: get_CompressionLevel()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt den Kompressionsgrad an, der beim Speichern des Präsentationsdokuments verwendet wird. Der Standardwert ist CompressionLevel::Level6."
type: docs
weight: 79
url: /de/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() Methode

Gibt den Kompressionsgrad an, der beim Speichern des Präsentationsdokuments verwendet wird. Der Standardwert ist [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## Anmerkungen

Höhere Kompressionsgrade erzeugen kleinere Dateien, erfordern jedoch mehr Verarbeitungszeit. Das tatsächliche Kompressionsverhältnis hängt vom Inhalt der Präsentation ab.  

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Siehe auch

* Enum [CompressionLevel](../../compressionlevel/)
* Klasse [PptxOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)