---
title: set_CompressionLevel()
second_title: Aspose.Slides für C++ API Referenz
description: "Gibt den beim Speichern des Präsentationsdokuments zu verwendenden Komprimierungsgrad an. Der Standardwert ist CompressionLevel::Level6."
type: docs
weight: 92
url: /de/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) Methode

Gibt den beim Speichern des Präsentationsdokuments zu verwendenden Komprimierungsgrad an. Der Standardwert ist [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## Hinweise

Höhere Komprimierungsgrade erzeugen kleinere Dateien, benötigen jedoch mehr Verarbeitungszeit. Das tatsächliche Kompressionsverhältnis hängt vom Inhalt der Präsentation ab.

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
* Library [Aspose.Slides](../../../)