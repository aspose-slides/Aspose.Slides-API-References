---
title: get_RefreshThumbnail()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट करता है कि प्रस्तुति थंबनेल को रिफ्रेश किया जाएगा या नहीं। पढ़ें bool। डिफ़ॉल्ट मान true है।
type: docs
weight: 53
url: /hi/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() method


निर्दिष्ट करता है कि प्रस्तुति थंबनेल को रिफ्रेश किया जाएगा या नहीं। पढ़ें **bool**. डिफ़ॉल्ट मान **true** है।

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## टिप्पणी


जब विकल्प मान **true** हो, नया थंबनेल जेनरेट किया जाएगा।

जब विकल्प मान **false** हो, वर्तमान थंबनेल जैसा का तैसा सहेजा जाएगा।

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## देखें

* क्लास [IPptxOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)