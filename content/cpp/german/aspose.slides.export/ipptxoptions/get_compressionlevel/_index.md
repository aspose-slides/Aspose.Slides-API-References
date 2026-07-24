---
title: get_CompressionLevel()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt das beim Speichern des Präsentationsdokuments verwendete Komprimierungsniveau an. Der Standardwert ist CompressionLevel::Level6."
type: docs
weight: 79
url: /de/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() Methode

Gibt das bei der Speicherung des Präsentationsdokuments verwendete Komprimierungsniveau an. Der Standardwert ist [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## Hinweise

Höhere Komprimierungsstufen erzeugen kleinere Dateien, benötigen jedoch mehr Verarbeitungszeit. Das tatsächliche Kompressionsverhältnis hängt vom Inhalt der Präsentation ab. 

Beispiel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Siehe auch

* Enum [CompressionLevel](../../compressionlevel/)
* Klasse [IPptxOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)