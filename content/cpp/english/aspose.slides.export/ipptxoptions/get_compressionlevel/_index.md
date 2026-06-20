---
title: get_CompressionLevel()
second_title: Aspose.Slides for C++ API Reference
description: "Specifies the compression level used when saving the presentation document. The default value is CompressionLevel::Level6."
type: docs
weight: 79
url: /aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() method


Specifies the compression level used when saving the presentation document. The default value is [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
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
* Class [IPptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)