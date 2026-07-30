---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace ISlidesLayoutOptions.
type: docs
weight: 1
url: /cs/aspose.slides.export/htmloptions/get_slideslayoutoptions/
---
## HtmlOptions::get_SlidesLayoutOptions() metoda

Získá režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::HtmlOptions::get_SlidesLayoutOptions() override
```

## Poznámky


Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [ISlidesLayoutOptions](../../islideslayoutoptions/)
* třída [HtmlOptions](../)
* jmenný prostor [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)