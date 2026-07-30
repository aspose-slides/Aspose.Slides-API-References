---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides pro C++ – reference API
description: Nastavuje režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace ISlidesLayoutOptions.
type: docs
weight: 183
url: /cs/aspose.slides.export/tiffoptions/set_slideslayoutoptions/
---
## TiffOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) metoda


Nastavuje režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::TiffOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## Poznámky


Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Třída [TiffOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)