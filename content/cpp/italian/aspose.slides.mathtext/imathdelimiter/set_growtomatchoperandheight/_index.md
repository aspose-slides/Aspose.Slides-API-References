---
title: set_GrowToMatchOperandHeight()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando. Il valore predefinito è true
type: docs
weight: 105
url: /it/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) metodo

Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando. Il valore predefinito è true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
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