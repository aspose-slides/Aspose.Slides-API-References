---
title: set_Character()
second_title: Riferimento API Aspose.Slides per C++
description: "Carattere di raggruppamento Valore predefinito: U+23DF (parentesi graffa inferiore)"
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathgroupingcharacter/set_character/
---
## MathGroupingCharacter::set_Character(char16_t) metodo

Carattere di raggruppamento Valore predefinito: U+23DF (parentesi graffa inferiore)

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_Character(char16_t value) override
```

## Osservazioni


Esempio: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Parentesi inferiore
```

## Vedi anche

* Classe [MathGroupingCharacter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)