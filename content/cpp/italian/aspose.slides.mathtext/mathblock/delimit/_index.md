---
title: Delimit()
second_title: Riferimento API di Aspose.Slides per C++
description: Delimita gli elementi figlio con il carattere separatore (senza parentesi)
type: docs
weight: 209
url: /it/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) metodo

Delimita gli elementi figlio con il carattere separatore (senza parentesi)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| separatorCharacter | char16_t | Carattere separatore |

### Valore restituito

L'elemento matematico di tipo [IMathDelimiter](../../imathdelimiter/)

## Osservazioni



Esempio: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [MathBlock](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)