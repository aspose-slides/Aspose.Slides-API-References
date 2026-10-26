---
title: set_Zip64Mode()
second_title: Aspose.Slides C++ API-referencia
description: "Megadja, hogy a ZIP64 formátumot használják-e a Presentation dokumentum esetén. Az alapértelmezett érték a Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /hu/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) metódus

Megadja, hogy a ZIP64 formátumot használják-e a [Presentation](../../../aspose.slides/presentation/) dokumentum esetén. Az alapértelmezett érték [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
```

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Lásd még

* Enum [Zip64Mode](../../zip64mode/)
* Osztály [PptxOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)