---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides per C++ API Reference
description: Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando. Il valore predefinito è true
type: docs
weight: 105
url: /it/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) metodo

Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando è true, i delimitatori crescono verticalmente per corrispondere all'altezza dell'operando. Il valore predefinito è true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```
## Osservazioni

Esempio: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```
## Vedi anche

* Classe [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)