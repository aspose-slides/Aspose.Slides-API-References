---
title: set_RefreshThumbnail()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट करता है कि प्रस्तुति थंबनेल रिफ्रेश किया जाएगा या नहीं। लिखें bool। डिफ़ॉल्ट मान true है।
type: docs
weight: 66
url: /hi/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) विधि

निर्दिष्ट करता है कि प्रस्तुति थंबनेल रिफ्रेश किया जाएगा या नहीं। लिखें **bool**। डिफ़ॉल्ट मान **true** है।

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
```

## टिप्पणियाँ

जब विकल्प मान **true** हो, नया थंबनेल उत्पन्न किया जाएगा।

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