---
title: set_BeginningCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: "Delimiter Beginning Character specifica il carattere delimitatore di inizio, o di apertura. I delimitatori matematici sono caratteri di chiusura come parentesi tonde, parentesi quadre e parentesi graffe. Il valore predefinito: '('."
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) metodo

Delimiter Beginning Character specifica il carattere delimitatore di inizio, o di apertura. I delimitatori matematici sono caratteri di chiusura come parentesi tonde, parentesi quadre e parentesi graffe. Il valore predefinito: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
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