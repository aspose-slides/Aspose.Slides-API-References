---
title: set_AnimateShapes()
second_title: Aspose.Slides for C++ API Reference
description: Sets shapes animation option. Write bool.
type: docs
weight: 40
url: /cpp/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(**bool**) method


Sets shapes animation option. Write **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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
