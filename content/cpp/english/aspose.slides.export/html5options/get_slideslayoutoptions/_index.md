---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Reference
description: Gets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptions.
type: docs
weight: 157
url: /aspose.slides.export/html5options/get_slideslayoutoptions/
---
## Html5Options::get_SlidesLayoutOptions() method


Gets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::Html5Options::get_SlidesLayoutOptions() override
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Class [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)