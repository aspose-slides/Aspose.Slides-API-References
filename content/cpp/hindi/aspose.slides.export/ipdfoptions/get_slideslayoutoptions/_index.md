---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक प्रस्तुति निर्यात करते समय स्लाइड्स पेज पर जिस मोड में रखी जाती हैं, उसे प्राप्त करता है ISlidesLayoutOptions।
type: docs
weight: 365
url: /hi/aspose.slides.export/ipdfoptions/get_slideslayoutoptions/
---
## IPdfOptions::get_SlidesLayoutOptions() विधि


एक प्रस्तुति निर्यात करते समय स्लाइड्स पेज पर किस मोड में रखी जाती हैं, इसे प्राप्त करता है [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IPdfOptions::get_SlidesLayoutOptions()=0
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

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [ISlidesLayoutOptions](../../islideslayoutoptions/)
* क्लास [IPdfOptions](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)