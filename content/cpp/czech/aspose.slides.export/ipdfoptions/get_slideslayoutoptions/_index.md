---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides pro referenční příručku API C++
description: Získá režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace ISlidesLayoutOptions.
type: docs
weight: 365
url: /cs/aspose.slides.export/ipdfoptions/get_slideslayoutoptions/
---
## IPdfOptions::get_SlidesLayoutOptions() metoda

Získá režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IPdfOptions::get_SlidesLayoutOptions()=0
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
* Třída [IPdfOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)