---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar läget i vilket bilder placeras på sidan när en presentation exporteras ISlidesLayoutOptions.
type: docs
weight: 170
url: /sv/aspose.slides.export/tiffoptions/get_slideslayoutoptions/
---
## TiffOptions::get_SlidesLayoutOptions() metod


Hämtar läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::TiffOptions::get_SlidesLayoutOptions() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Klass [TiffOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)