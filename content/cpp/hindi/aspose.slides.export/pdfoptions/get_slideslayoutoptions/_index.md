---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API संदर्भ
description: प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है ISlidesLayoutOptions.
type: docs
weight: 1
url: /hi/aspose.slides.export/pdfoptions/get_slideslayoutoptions/
---
## PdfOptions::get_SlidesLayoutOptions() विधि

प्रस्तुति निर्यात करते समय स्लाइड्स को पृष्ठ पर रखने के मोड को प्राप्त करता है [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::PdfOptions::get_SlidesLayoutOptions() override
```

## टिप्पणियाँ

उदाहरण:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## देखें भी

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Class [PdfOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)