---
title: set_Zip64Mode()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Określa, czy format ZIP64 jest używany dla dokumentu Presentation. Domyślna wartość to Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /pl/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) metoda


Określa, czy format ZIP64 jest używany dla dokumentu [Presentation](../../../aspose.slides/presentation/). Domyślna wartość to [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
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

* Enum [Zip64Mode](../../zip64mode/)
* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)