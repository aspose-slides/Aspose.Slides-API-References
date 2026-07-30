---
title: idx_get()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera l'elemento all'indice specificato. IMathElement di sola lettura.
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(int32_t) metodo


Recupera l'elemento all'indice specificato. Sola lettura [IMathElement](../../imathelement/).

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero dell'elemento da ottenere |
## Osservazioni



Esempio: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)