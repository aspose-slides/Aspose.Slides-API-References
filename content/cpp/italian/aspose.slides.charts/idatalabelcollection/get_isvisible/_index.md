---
title: get_IsVisible()
second_title: Riferimento API di Aspose.Slides per C++
description: False significa che l'etichetta dati non è visibile per impostazione predefinita (e quindi tutti i flag Show*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat sono false). Solo lettura bool.
type: docs
weight: 27
url: /it/aspose.slides.charts/idatalabelcollection/get_isvisible/
---
## IDataLabelCollection::get_IsVisible() metodo

False means that data label is not visible by default (and so all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). Solo lettura **bool**.

```cpp
virtual bool Aspose::Slides::Charts::IDataLabelCollection::get_IsVisible()=0
```

## Osservazioni

Se l'etichetta dati è visibile per impostazione predefinita, è possibile renderla nascosta per impostazione predefinita con il metodo [Hide()](../hide/). Ma se l'etichetta dati non è visibile per impostazione predefinita (IsVisible è false) è possibile rendere l'etichetta dati "visibile per impostazione predefinita" impostando i flag Show*-flags (ShowValue, ...) della proprietà DefaultDataLabelFormat su true.

## Vedi anche

* Classe [IDataLabelCollection](../)
* Namespace [Aspose::Slides::Charts](../../)
* Libreria [Aspose.Slides](../../../)