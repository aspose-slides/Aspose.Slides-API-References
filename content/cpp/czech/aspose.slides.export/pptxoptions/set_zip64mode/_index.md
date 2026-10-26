---
title: set_Zip64Mode()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: "Určuje, zda je pro dokument Presentation použit formát ZIP64. Výchozí hodnota je Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /cs/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) metoda

Určuje, zda je formát ZIP64 použit pro dokument [Presentation](../../../aspose.slides/presentation/). Výchozí hodnota je [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
```

## Poznámky


Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Viz také

* Enum [Zip64Mode](../../zip64mode/)
* třída [PptxOptions](../)
* jmenný prostor [Aspose::Slides::Export](../../)
* knihovna [Aspose.Slides](../../../)