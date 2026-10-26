---
title: set_Zip64Mode()
second_title: Aspose.Slides för C++ API-referens
description: "Anger om ZIP64-formatet används för Presentation-dokumentet. Standardvärdet är Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /sv/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) metod


Anger om ZIP64-formatet används för [Presentation](../../../aspose.slides/presentation/)-dokumentet. Standardvärdet är [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Se också

* Enum [Zip64Mode](../../zip64mode/)
* Klass [PptxOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)