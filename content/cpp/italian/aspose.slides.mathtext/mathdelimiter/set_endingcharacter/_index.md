---
title: set_EndingCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il carattere di chiusura del delimitatore specifica il carattere finale, o di chiusura, del delimitatore. I delimitatori matematici sono caratteri di contenimento come parentesi tonde, quadre e graffe. Il valore predefinito: ')'."
type: docs
weight: 79
url: /it/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) metodo


Il carattere di chiusura del delimitatore specifica il carattere finale, o di chiusura, del delimitatore. I delimitatori matematici sono caratteri di contenimento come parentesi tonde, quadre e graffe. Il valore predefinito: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## Osservazioni


Esempio: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Vedi anche

* Classe [MathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)