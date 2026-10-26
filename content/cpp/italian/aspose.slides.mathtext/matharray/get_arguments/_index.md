---
title: get_Arguments()
second_title: Riferimento API di Aspose.Slides per C++
description: L'insieme degli elementi dell'array
type: docs
weight: 1
url: /it/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() metodo


L'insieme degli elementi dell'array

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
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
* Classe [MathArray](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)