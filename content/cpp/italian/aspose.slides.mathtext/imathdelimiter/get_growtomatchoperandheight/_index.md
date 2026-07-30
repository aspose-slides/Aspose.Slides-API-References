---
title: get_GrowToMatchOperandHeight()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando. Il valore predefinito è true
type: docs
weight: 92
url: /it/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() metodo

Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando è true, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando. Il valore predefinito è true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## Osservazioni

Esempio: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Vedi anche

* Classe [IMathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)