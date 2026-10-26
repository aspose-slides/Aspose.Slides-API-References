---
title: Remove()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove un layout dalla collezione.
type: docs
weight: 66
url: /it/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) metodo


Rimuove un layout dalla collezione.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Il layout slide da rimuovere dalla collezione. |
## Osservazioni



1) Per evitare il lancio di PptxEditException, controllare prima la proprietà HasDependingSlides del layout. 2) Puoi anche utilizzare il metodo [ILayoutSlide::Remove](../../ilayoutslide/remove/) per semplificare il codice. 
## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [LayoutSlideCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)