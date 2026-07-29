---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar läget i vilket bilder placeras på sidan vid export av en presentation ISlidesLayoutOptions.
type: docs
weight: 157
url: /sv/aspose.slides.export/ihtml5options/get_slideslayoutoptions/
---
## IHtml5Options::get_SlidesLayoutOptions() metod


Hämtar läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::IHtml5Options::get_SlidesLayoutOptions()=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klass [IHtml5Options](../)
* Namnutrymme [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)