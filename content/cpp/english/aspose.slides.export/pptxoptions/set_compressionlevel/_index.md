---
title: set_CompressionLevel()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies the compression level used when saving the presentation document. The default value is CompressionLevel::Level6."
type: docs
weight: 92
url: /aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) method


Specifies the compression level used when saving the presentation document. The default value is [CompressionLevel::Level6](../../compressionlevel/).

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## Remarks


Higher compression levels produce smaller files but require more processing time. The actual compression ratio depends on the content of the presentation. 

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## See Also

* Enum [CompressionLevel](../../compressionlevel/)
* Class [PptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)