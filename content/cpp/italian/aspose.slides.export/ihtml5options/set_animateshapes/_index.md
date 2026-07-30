---
title: set_AnimateShapes()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta l'opzione di animazione delle forme. Scrivi bool.
type: docs
weight: 40
url: /it/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) metodo

Imposta l'opzione di animazione delle forme. Scrivi **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
```

## Osservazioni


Esempio: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Vedi anche

* Classe [IHtml5Options](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)