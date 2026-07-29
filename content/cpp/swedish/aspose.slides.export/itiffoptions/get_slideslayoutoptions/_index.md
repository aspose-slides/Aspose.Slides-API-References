---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar läget där bilder placeras på sidan när en presentation exporteras ISlidesLayoutOptions.
type: docs
weight: 157
url: /sv/aspose.slides.export/itiffoptions/get_slideslayoutoptions/
---
## ITiffOptions::get_SlidesLayoutOptions() metod


Hämtar läget där bilder placeras på sidan när en presentation exporteras [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ITiffOptions::get_SlidesLayoutOptions()=0
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
* Klass [ITiffOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)