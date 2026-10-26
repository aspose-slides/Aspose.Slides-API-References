---
title: get_SeparatorCharacter()
second_title: Riferimento API di Aspose.Slides per C++
description: "Delimiter Separator Character specifica il carattere che separa gli argomenti nell'oggetto delimitatore. Il valore predefinito: '|'."
type: docs
weight: 40
url: /it/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() metodo

Delimiter Separator Character specifica il carattere che separa gli argomenti nell'oggetto delimitatore. Il valore predefinito: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## Osservazioni

Esempio:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Vedi anche

* Classe [IMathDelimiter](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)