---
title: set_CompressionLevel()
second_title: Aspose.Slides für C++ API Referenz
description: "Gibt das beim Speichern des Präsentationsdokuments zu verwendende Komprimierungsniveau an. Der Standardwert ist CompressionLevel::Level6."
type: docs
weight: 92
url: /de/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) Methode


Gibt das beim Speichern des Präsentationsdokuments zu verwendende Komprimierungsniveau an. Der Standardwert ist [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## Hinweise


Höhere Komprimierungsstufen erzeugen kleinere Dateien, erfordern jedoch mehr Verarbeitungszeit. Das tatsächliche Kompressionsverhältnis hängt vom Inhalt der Präsentation ab. 

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Siehe auch

* Enum [CompressionLevel](../../compressionlevel/)
* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)