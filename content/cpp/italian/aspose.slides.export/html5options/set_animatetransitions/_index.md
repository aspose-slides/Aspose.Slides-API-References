---
title: set_AnimateTransitions()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta l'opzione di animazione delle transizioni. Scrivi bool.
type: docs
weight: 14
url: /it/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) metodo


Imposta l'opzione di animazione delle transizioni. Scrivi **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
```

## Osservazioni


Esempio: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Vedi anche

* Classe [Html5Options](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)