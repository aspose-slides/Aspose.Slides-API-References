---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace ISlidesLayoutOptions.
type: docs
weight: 157
url: /cs/aspose.slides.export/ihtml5options/get_slideslayoutoptions/
---
## IHtml5Options::get_SlidesLayoutOptions() metoda

Získá režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtml5Options::get_SlidesLayoutOptions()=0
```

## Poznámky

Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Třída [IHtml5Options](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)