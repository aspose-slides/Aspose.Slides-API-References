---
title: get_Character()
second_title: Aspose.Slides per C++ Riferimento API
description: "Carattere di raggruppamento valore predefinito: U+23DF (parentesi graffa inferiore)"
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() metodo

Grouping Character Valore predefinito: U+23DF (parentesi graffa inferiore)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
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
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)