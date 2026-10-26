---
title: set_SeparatorCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: "Delimiter Separator Character specifica il carattere che separa gli argomenti nell'oggetto delimitatore. Il valore predefinito: '|'."
type: docs
weight: 53
url: /it/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) metodo


Delimiter Separator Character specifica il carattere che separa gli argomenti nell'oggetto delimitatore. Il valore predefinito: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Osservazioni


Esempio: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Vedi anche

* Classe [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)