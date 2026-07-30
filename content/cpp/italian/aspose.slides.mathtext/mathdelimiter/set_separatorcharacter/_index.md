---
title: set_SeparatorCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: "Il carattere separatore del delimitatore specifica il carattere che separa gli argomenti nell'oggetto delimiter. Predefinito: '|'."
type: docs
weight: 53
url: /it/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) metodo

Delimiter Separator Character specifica il carattere che separa gli argomenti nell'oggetto delimiter. Il valore predefinito: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## Osservazioni

Esempio:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Vedi anche

* Classe [MathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)