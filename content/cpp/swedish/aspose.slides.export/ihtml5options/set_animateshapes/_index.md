---
title: set_AnimateShapes()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in alternativet för animering av former. Skriv bool.
type: docs
weight: 40
url: /sv/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) metod


Ställer in alternativet för animering av former. Skriv **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
```

## Anmärkningar


Exempel: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Se också

* Klass [IHtml5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)