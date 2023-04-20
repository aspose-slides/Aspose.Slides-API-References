---
title: get_SufficientResolution()
second_title: Aspose.Slides for C++ API Reference
description: Returns a value determining resolution of images inside PDF document.
type: docs
weight: 287
url: /cpp/aspose.slides.export/ipdfoptions/get_sufficientresolution/
---
## IPdfOptions::get_SufficientResolution() method


Returns a value determining resolution of images inside PDF document.

```cpp
virtual float Aspose::Slides::Export::IPdfOptions::get_SufficientResolution()=0
```

## Remarks


Property affects on file size, time of export and image quality.

The default value is **96**.

Effect of this parameter depends on few factors. Algorithm tries to get best output image size according to the property value, source image size and image frame size. Using of similar property values may give the same result. Recommended to use step 16 or 32 to get visible effect.

Read **float**. 
## See Also

* Class [IPdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)