---
title: set_Zip64Mode()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt an, ob das ZIP64-Format für das Präsentationsdokument verwendet wird. Der Standardwert ist Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /de/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) Methode

Gibt an, ob das ZIP64-Format für das [Presentation](../../../aspose.slides/presentation/)-Dokument verwendet wird. Der Standardwert ist [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
```

## Bemerkungen

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Siehe auch

* Aufzählung [Zip64Mode](../../zip64mode/)
* Klasse [IPptxOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)