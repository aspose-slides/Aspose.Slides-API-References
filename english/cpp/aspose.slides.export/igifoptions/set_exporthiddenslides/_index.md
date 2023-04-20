---
title: set_ExportHiddenSlides()
second_title: Aspose.Slides for C++ API Reference
description: Determines whether hidden slides will be exported. The default value is false.
type: docs
weight: 40
url: /cpp/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) method


Determines whether hidden slides will be exported. The default value is false.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
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