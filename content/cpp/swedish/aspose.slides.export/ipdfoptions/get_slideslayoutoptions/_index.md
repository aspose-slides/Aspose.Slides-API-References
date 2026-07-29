---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar läget i vilket bilder placeras på sidan vid export av en presentation ISlidesLayoutOptions.
type: docs
weight: 365
url: /sv/aspose.slides.export/ipdfoptions/get_slideslayoutoptions/
---
## IPdfOptions::get_SlidesLayoutOptions() metod

Hämtar läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IPdfOptions::get_SlidesLayoutOptions()=0
```
## Anmärkningar

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klass [IPdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)