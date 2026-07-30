---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace ISlidesLayoutOptions.
type: docs
weight: 14
url: /cs/aspose.slides.export/pdfoptions/set_slideslayoutoptions/
---
## PdfOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) method

Nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## Poznámky

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Třída [PdfOptions](../)
* Prostor názvů [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)