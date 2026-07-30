---
title: get_AnimateTransitions()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce l'opzione di animazione delle transizioni. Leggi bool.
type: docs
weight: 1
url: /it/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() metodo


Restituisce l'opzione di animazione delle transizioni. Leggi **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
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

* Classe [IHtml5Options](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)