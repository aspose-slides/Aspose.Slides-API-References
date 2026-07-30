---
title: set_BeginningCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il carattere di inizio delimitatore specifica il carattere di inizio, o di apertura, del delimitatore. I delimitatori matematici sono caratteri di delimitazione come parentesi tonde, parentesi quadre e graffe. Il valore predefinito: '('."
type: docs
weight: 27
url: /it/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) metodo


Il carattere iniziale del delimitatore specifica il carattere di inizio, o di apertura, del delimitatore. I delimitatori matematici sono caratteri di delimitazione come parentesi, parentesi quadre e graffe. Il valore predefinito: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## Osservazioni


Esempio: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Vedi anche

* Classe [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)