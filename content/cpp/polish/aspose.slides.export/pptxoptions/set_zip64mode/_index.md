---
title: set_Zip64Mode()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: "Określa, czy format ZIP64 jest używany dla dokumentu Presentation. Domyślna wartość to Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /pl/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) metoda


Określa, czy format ZIP64 jest używany dla dokumentu [Presentation](../../../aspose.slides/presentation/). Domyślna wartość to [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Zobacz także

* Wyliczenie [Zip64Mode](../../zip64mode/)
* Klasa [PptxOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)