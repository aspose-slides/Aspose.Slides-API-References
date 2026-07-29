---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar läget i vilket bilder placeras på sidan när en presentation exporteras ISlidesLayoutOptions.
type: docs
weight: 1
url: /sv/aspose.slides.export/htmloptions/get_slideslayoutoptions/
---
## HtmlOptions::get_SlidesLayoutOptions() metod


Hämtar läget på vilket bilder placeras på sidan när en presentation exporteras [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::HtmlOptions::get_SlidesLayoutOptions() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klass [HtmlOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)