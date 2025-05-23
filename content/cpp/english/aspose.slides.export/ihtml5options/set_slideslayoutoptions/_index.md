---
title: set_SlidesLayoutOptions()
second_title: Aspose.Slides for C++ API Reference
description: Sets the mode in which slides are placed on the page when exporting a presentation ISlidesLayoutOptions.
type: docs
weight: 170
url: /aspose.slides.export/ihtml5options/set_slideslayoutoptions/
---
## IHtml5Options::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) method


Sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
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
* Class [IHtml5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)