---
title: get_GrowToMatchOperandHeight()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando è vero, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando. Il valore predefinito è vero
type: docs
weight: 92
url: /it/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() metodo

Specifica la crescita di BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando vero, i delimitatori crescono verticalmente per corrispondere all'altezza del loro operando. Il valore predefinito è vero

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Osservazioni

Esempio:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Vedi anche

* Classe [MathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)