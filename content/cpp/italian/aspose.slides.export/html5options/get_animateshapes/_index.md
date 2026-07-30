---
title: get_AnimateShapes()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce l'opzione di animazione delle forme. Leggi bool.
type: docs
weight: 27
url: /it/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() metodo


Restituisce l'opzione di animazione delle forme. Leggi **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
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

* Classe [Html5Options](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)