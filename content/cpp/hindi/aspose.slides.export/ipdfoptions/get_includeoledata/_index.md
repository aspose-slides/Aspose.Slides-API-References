---
title: get_IncludeOleData()
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: सही सभी OLE डेटा को प्रस्तुति से परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए। पढ़ें bool.
type: docs
weight: 456
url: /hi/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() मेथड


प्रस्तुति से सभी OLE डेटा को परिणामी PDF में एम्बेडेड फ़ाइलों में बदलने के लिए true लौटाता है। पढ़ें **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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

* क्लास [IPdfOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)