---
title: set_Zip64Mode()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies whether the ZIP64 format is used for the Presentation document. The default value is Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) method


Specifies whether the ZIP64 format is used for the [Presentation](../../../aspose.slides/presentation/) document. The default value is [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## See Also

* Enum [Zip64Mode](../../zip64mode/)
* Class [PptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)