---
title: set_SufficientResolution()
second_title: Aspose.Slides for C++ API Reference
description: Sets a value determining resolution of images inside PDF document.
type: docs
weight: 352
url: /aspose.slides.export/pdfoptions/set_sufficientresolution/
---
## PdfOptions::set_SufficientResolution(float) method


Sets a value determining resolution of images inside PDF document.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SufficientResolution(float value) override
```

## Remarks


Property affects on file size, time of export and image quality.

The default value is **96**.

Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

Write **float**. 
## See Also

* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)