---
title: get_BeginningCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: "Delimiter Beginning Character specifica il carattere di delimitazione iniziale, o di apertura. I delimitatori matematici sono caratteri di racchiusura come parentesi tonde, parentesi quadre e parentesi graffe. Il valore predefinito: '('."
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() metodo


Delimiter Beginning Character specifica il carattere di delimitazione iniziale, o di apertura. I delimitatori matematici sono caratteri di racchiusura come parentesi tonde, parentesi quadre e parentesi graffe. Il valore predefinito: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Osservazioni


Esempio: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Vedi anche

* Classe [MathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)