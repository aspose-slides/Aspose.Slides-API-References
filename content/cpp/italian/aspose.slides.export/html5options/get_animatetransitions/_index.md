---
title: get_AnimateTransitions()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce l'opzione di animazione delle transizioni. Leggi bool.
type: docs
weight: 1
url: /it/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() metodo


Restituisce l'opzione di animazione delle transizioni. Leggi **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
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