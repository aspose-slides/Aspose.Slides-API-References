---
title: set_JpegQuality()
second_title: Aspose.Slides for C++ API Reference
description: Sets a value determining the quality of the JPEG images inside PDF document. Write uint8_t.
type: docs
weight: 183
url: /cpp/aspose.slides.export/pdfoptions/set_jpegquality/
---
## PdfOptions::set_JpegQuality(uint8_t) method


Sets a value determining the quality of the JPEG images inside PDF document. Write **uint8_t**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_JpegQuality(uint8_t value) override
```

## Remarks


Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **100**.
## See Also

* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)