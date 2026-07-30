---
title: set_Character()
second_title: Riferimento API Aspose.Slides per C++
description: "Carattere di raggruppamento Valore predefinito: U+23DF (parentesi graffa inferiore)"
type: docs
weight: 27
url: /it/aspose.slides.mathtext/imathgroupingcharacter/set_character/
---
## IMathGroupingCharacter::set_Character(char16_t) metodo


Carattere di raggruppamento Valore predefinito: U+23DF (parentesi graffa inferiore)

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_Character(char16_t value)=0
```

## Osservazioni


Esempio: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Parentesi inferiore
```

## Vedi anche

* Classe [IMathGroupingCharacter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)