---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in läget där bilder placeras på sidan vid export av en presentation ISlidesLayoutOptions.
type: docs
weight: 14
url: /sv/aspose.slides.export/pdfoptions/set_slideslayoutoptions/
---
## PdfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metod


Ställer in läget där bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klass [PdfOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)