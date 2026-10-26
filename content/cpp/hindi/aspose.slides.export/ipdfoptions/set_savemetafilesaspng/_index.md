---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: प्रेज़ेंटेशन में उपयोग किए गए सभी मेटाफाइल्स को PNG इमेजेज़ में परिवर्तित करने के लिए True सेट करें। Write bool.
type: docs
weight: 300
url: /hi/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) विधि

True to convert all metafiles used in a presentation to the PNG images. Write **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## टिप्पणी

Default is **true**. Pdf document can contain vector graphics and raster images. If SaveMetafilesAsPng is set to true then source Metafile image is converted to Png format and saved to Pdf as a raster image. If SaveMetafilesAsPng is set to false then source Metafile is converted to Pdf vector graphics. Each approach has advantages and disadvantages. For example, if Metafile is converted to PNG, then some quality loss is possible during resulting document scaling. If Metafile is converted to Pdf vector graphics, then performance issues in Pdf viewing tool are possible.

## देखें

* क्लास [IPdfOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लायब्रेरी [Aspose.Slides](../../../)