---
title: set_JpegQuality()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet. Skriv uint8_t.
type: docs
weight: 235
url: /sv/aspose.slides.export/pdfoptions/set_jpegquality/
---
## PdfOptions::set_JpegQuality(uint8_t) metod

Sets a value determining the quality of the JPEG images inside PDF document. Write **uint8_t**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_JpegQuality(uint8_t value) override
```

## Anmärkningar

Has effect only when a document contains JPEG images.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **100**.

## Se även

* Klass [PdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)