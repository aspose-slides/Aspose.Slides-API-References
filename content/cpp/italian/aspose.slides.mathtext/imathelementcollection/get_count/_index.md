---
title: get_Count()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce il numero di elementi effettivamente contenuti nella raccolta. Sola lettura int32_t.
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() metodo

Restituisce il numero di elementi effettivamente contenuti nella raccolta. Sola lettura **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```

## Osservazioni

Esempio:
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```

## Vedi anche

* Classe [IMathElementCollection](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)