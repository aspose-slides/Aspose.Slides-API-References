---
title: set_EndingCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: "Delimiter Ending Character specifica il carattere di delimitazione finale, o di chiusura. I delimitatori matematici sono caratteri di incapsulamento come parentesi tonde, parentesi quadre e graffe. Il valore predefinito: ')'."
type: docs
weight: 79
url: /it/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) metodo


Delimiter Ending Character specifica il carattere di delimitazione finale, o di chiusura. I delimitatori matematici sono caratteri di incapsulamento come parentesi tonde, parentesi quadre e graffe. Il valore predefinito: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## Osservazioni


Esempio: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Vedi anche

* Classe [IMathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)