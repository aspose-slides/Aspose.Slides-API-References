---
title: get_EndingCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il carattere di chiusura del delimitatore specifica il carattere delimitatore finale o di chiusura. I delimitatori matematici sono caratteri di delimitazione come parentesi tonde, parentesi quadre e parentesi graffe. Il valore predefinito: ')'."
type: docs
weight: 66
url: /it/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() metodo


Il carattere di chiusura del delimitatore specifica il carattere delimitatore di chiusura, o finale. I delimitatori matematici sono caratteri di delimitazione come parentesi tonde, parentesi quadre e parentesi graffe. Il valore predefinito: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
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