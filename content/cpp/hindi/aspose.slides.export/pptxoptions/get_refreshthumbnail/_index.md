---
title: get_RefreshThumbnail()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट करता है कि प्रस्तुति थंबनेल को रीफ़्रेश किया जाएगा या नहीं। पढ़ें bool। डिफ़ॉल्ट मान true है।
type: docs
weight: 53
url: /hi/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() मेथड

निर्दिष्ट करता है कि प्रस्तुति थंबनेल को रीफ़्रेश किया जाएगा या नहीं। पढ़ें **bool**। डिफ़ॉल्ट मान **true** है।

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## टिप्पणियाँ

जब विकल्प मान **true** हो, नया थंबनेल उत्पन्न किया जाएगा।

जब विकल्प मान **false** हो, वर्तमान थंबनेल जैसा का वैसा सहेजा जाएगा।

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## देखें

* क्लास [PptxOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)