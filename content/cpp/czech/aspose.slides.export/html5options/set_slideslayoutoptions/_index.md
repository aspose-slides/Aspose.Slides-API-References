---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides pro C++ – reference API
description: Nastaví režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace ISlidesLayoutOptions.
type: docs
weight: 170
url: /cs/aspose.slides.export/html5options/set_slideslayoutoptions/
---
## Html5Options::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) method

Nastaví režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::Html5Options::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
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
* třída [ISlidesLayoutOptions](../../islideslayoutoptions/)
* třída [Html5Options](../)
* jmenný prostor [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)