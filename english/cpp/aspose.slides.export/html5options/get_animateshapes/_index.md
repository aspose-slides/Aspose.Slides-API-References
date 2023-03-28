---
title: get_AnimateShapes()
second_title: Aspose.Slides for C++ API Reference
description: Returns shapes animation option. Read bool.
type: docs
weight: 27
url: /cpp/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() method


Returns shapes animation option. Read **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
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

* Class [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
