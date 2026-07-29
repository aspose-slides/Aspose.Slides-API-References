---
title: set_AnimateTransitions()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in övergångsanimationsalternativet. Skriv bool.
type: docs
weight: 14
url: /sv/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) metod


Ställer in övergångsanimationsalternativet. Skriv **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
```

## Anmärkningar


Exempel:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Se även

* Klass [Html5Options](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)