---
title: get_Arguments()
second_title: Aspose.Slides per il riferimento API di C++
description: L'insieme degli elementi dell'array
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() metodo


Il set di elementi dell'array

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## Osservazioni


Esempio: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElementCollection](../../imathelementcollection/)
* Classe [IMathArray](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)