---
title: set_Zip64Mode()
second_title: Aspose.Slides für C++ API-Referenz
description: "Gibt an, ob das ZIP64-Format für das Presentation-Dokument verwendet wird. Der Standardwert ist Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /de/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) method

Gibt an, ob das ZIP64-Format für das [Presentation](../../../aspose.slides/presentation/) Dokument verwendet wird. Der Standardwert ist [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
```

## Hinweise

Beispiel:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Siehe auch

* Enum [Zip64Mode](../../zip64mode/)
* Klasse [PptxOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)