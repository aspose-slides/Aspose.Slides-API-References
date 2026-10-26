---
title: get_SeparatorCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: "Delimiter Separator Character specifica il carattere che separa gli argomenti nell'oggetto delimitatore. Il valore predefinito: '|'."
type: docs
weight: 40
url: /it/aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() metodo

Delimiter Separator Character specifica il carattere che separa gli argomenti nell'oggetto delimitatore. Il valore predefinito: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
```

## Osservazioni


Esempio: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Vedi anche

* Classe [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)