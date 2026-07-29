---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar läget där bilder placeras på sidan när en presentation exporteras ISlidesLayoutOptions.
type: docs
weight: 157
url: /sv/aspose.slides.export/html5options/get_slideslayoutoptions/
---
## Html5Options::get_SlidesLayoutOptions() metod

Hämtar läget där bilder placeras på sidan när en presentation exporteras [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::Html5Options::get_SlidesLayoutOptions() override
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
* Klass [Html5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)