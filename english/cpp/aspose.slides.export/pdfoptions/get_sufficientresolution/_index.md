---
title: get_SufficientResolution()
second_title: Aspose.Slides for C++ API Reference
description: Returns a value determining resolution of images inside PDF document.
type: docs
weight: 300
url: /cpp/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() method


Returns a value determining resolution of images inside PDF document.

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## Remarks


Property affects on file size, time of export and image quality.

The default value is **96**.

Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

Read **float**. 
## See Also

* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
