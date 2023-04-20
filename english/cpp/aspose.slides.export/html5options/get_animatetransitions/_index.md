---
title: get_AnimateTransitions()
second_title: Aspose.Slides for C++ API Reference
description: Returns transitions animation option. Read bool.
type: docs
weight: 1
url: /cpp/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() method


Returns transitions animation option. Read **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## Remarks


Example: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## See Also

* Class [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)