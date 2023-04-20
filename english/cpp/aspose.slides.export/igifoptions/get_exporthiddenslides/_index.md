---
title: get_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether hidden slides will be exported. The default value is false.
type: docs
weight: 27
url: /cpp/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() method


Determines whether hidden slides will be exported. The default value is false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## See Also

* Class [IGifOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)