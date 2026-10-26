---
title: get_IncludeOleData()
second_title: Aspose.Slides for C++ API संदर्भ
description: सही यदि सभी OLE डेटा को प्रस्तुति से परिणामस्वरूप PDF में एम्बेडेड फ़ाइलों में बदलना हो। पढ़ें bool.
type: docs
weight: 456
url: /hi/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() विधि

सत्य यदि सभी OLE डेटा को प्रस्तुति से परिणामस्वरूप PDF में एम्बेडेड फ़ाइलों में बदलना हो। पढ़ें **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## टिप्पणियाँ

डिफ़ॉल्ट **false** है। 

उदाहरण: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## देखें भी

* वर्ग [PdfOptions](../)
* नामस्थान [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)