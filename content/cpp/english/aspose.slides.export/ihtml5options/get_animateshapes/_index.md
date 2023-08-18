---
title: get_AnimateShapes()
second_title: Aspose.Slides for C++ API Reference
description: Returns shapes animation option. Read bool.
type: docs
weight: 27
url: /aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() method


Returns shapes animation option. Read **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
```

## Remarks


Example: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## See Also

* Class [IHtml5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)