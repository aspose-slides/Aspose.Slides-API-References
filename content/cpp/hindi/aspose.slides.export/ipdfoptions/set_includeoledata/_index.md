---
title: set_IncludeOleData()
second_title: Aspose.Slides for C++ API संदर्भ
description: सभी OLE डेटा को प्रस्तुति से उत्पन्न PDF में एम्बेडेड फ़ाइलों में बदलने के लिए True सेट करें। लिखें bool.
type: docs
weight: 469
url: /hi/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) मेथड

True सेट करके प्रस्तुति से सभी OLE डेटा को उत्पन्न PDF में एम्बेडेड फ़ाइलों में परिवर्तित किया जाता है। लिखें **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
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