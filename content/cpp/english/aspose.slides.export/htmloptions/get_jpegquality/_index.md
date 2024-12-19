---
title: get_JpegQuality()
second_title: Aspose.Slides for C++ API Reference
description: Returns a value determining the quality of the JPEG images inside PDF document. Read uint8_t.
type: docs
weight: 118
url: /aspose.slides.export/htmloptions/get_jpegquality/
---
## HtmlOptions::get_JpegQuality() method


Returns a value determining the quality of the JPEG images inside PDF document. Read **uint8_t**.

```cpp
uint8_t Aspose::Slides::Export::HtmlOptions::get_JpegQuality() override
```

## Remarks


Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **95**.
## See Also

* Class [HtmlOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)