---
title: set_IncludeOleData()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: प्रेज़ेंटेशन से सभी OLE डेटा को परिणामस्वरूप PDF में एम्बेडेड फ़ाइलों में बदलने के लिए True सेट करें। Write bool.
type: docs
weight: 469
url: /hi/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) विधि


प्रेज़ेंटेशन से सभी OLE डेटा को परिणामस्वरूप PDF में एम्बेडेड फ़ाइलों में बदलने के लिए True सेट करें। लिखें **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
```

## टिप्पणी


डिफ़ॉल्ट **false** है। 

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## देखें

* क्लास [PdfOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)