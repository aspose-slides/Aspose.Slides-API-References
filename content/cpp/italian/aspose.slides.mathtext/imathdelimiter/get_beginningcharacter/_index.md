---
title: get_BeginningCharacter()
second_title: Riferimento API Aspose.Slides per C++
description: "Il carattere di delimitazione iniziale specifica il carattere di delimitazione di apertura. I delimitatori matematici sono caratteri di racchiusura come parentesi tonde, parentesi quadre e parentesi graffe. Il valore predefinito: '('."
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() method

Il carattere di delimitazione iniziale specifica il carattere di delimitazione di apertura. I delimitatori matematici sono caratteri di racchiusura come parentesi tonde, parentesi quadre e parentesi graffe. Il valore predefinito: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Osservazioni

Esempio:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Vedi anche

* Classe [IMathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)