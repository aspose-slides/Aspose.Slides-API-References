---
title: get_JpegQuality()
second_title: Aspose.Slides for C++ API Reference
description: Returns a value determining the quality of the JPEG images inside PDF document. Read uint8_t.
type: docs
weight: 157
url: /aspose.slides.export/ipdfoptions/get_jpegquality/
---
## IPdfOptions::get_JpegQuality() method


Returns a value determining the quality of the JPEG images inside PDF document. Read **uint8_t**.

```cpp
virtual uint8_t Aspose::Slides::Export::IPdfOptions::get_JpegQuality()=0
```

## Remarks


Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **100**.
## See Also

* Class [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)