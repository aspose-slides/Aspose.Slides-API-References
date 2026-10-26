---
title: Remove()
second_title: Aspose.Slides per C++ Riferimento API
description: Rimuove un layout dalla collezione.
type: docs
weight: 27
url: /it/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) metodo


Rimuove un layout dalla collezione.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | La diapositiva di layout da rimuovere dalla collezione. |
## Osservazioni



1) Per evitare il lancio di PptxEditException controllare la proprietà HasDependingSlides di layout prima. 2) Puoi anche usare il metodo [ILayoutSlide::Remove](../../ilayoutslide/remove/) per semplificare il codice. 
## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [ILayoutSlideCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)