---
title: set_AnimateShapes()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in animeringsalternativ för former. Skriv bool.
type: docs
weight: 40
url: /sv/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) metod


Ställer in animeringsalternativ för former. Skriv **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
```

## Anmärkningar


Example: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Se även

* Klass [Html5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)