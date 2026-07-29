---
title: get_AnimateShapes()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alternativet för animering av former. Läs bool.
type: docs
weight: 27
url: /sv/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() metod


Returnerar alternativet för animering av former. Läs **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
```

## Anmärkningar


Exempel:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Se även

* Klass [IHtml5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)