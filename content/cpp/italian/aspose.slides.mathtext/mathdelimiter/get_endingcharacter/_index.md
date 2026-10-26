---
title: get_EndingCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il Carattere finale del delimitatore specifica il carattere di chiusura del delimitatore. I delimitatori matematici sono caratteri di incapsulamento come le parentesi tonde, le parentesi quadre e le parentesi graffe. Il valore predefinito: ')'."
type: docs
weight: 66
url: /it/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() metodo


Il Carattere finale del delimitatore specifica il carattere di chiusura del delimitatore. I delimitatori matematici sono caratteri di incapsulamento come le parentesi tonde, le parentesi quadre e le parentesi graffe. Il valore predefinito: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
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