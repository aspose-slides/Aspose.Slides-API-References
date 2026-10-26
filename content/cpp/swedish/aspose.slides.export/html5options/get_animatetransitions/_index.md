---
title: get_AnimateTransitions()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar alternativet för övergångsanimation. Läs bool.
type: docs
weight: 1
url: /sv/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() metod


Returnerar alternativet för övergångsanimation. Läs **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
```

## Anmärkningar


Exempel: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Se också

* Klass [Html5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)