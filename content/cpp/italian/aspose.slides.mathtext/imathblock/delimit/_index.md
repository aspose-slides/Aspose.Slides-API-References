---
title: Delimit()
second_title: Riferimento API Aspose.Slides per C++
description: Delimita tutti gli elementi figli con il carattere separatore (senza le parentesi)
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) metodo


Delimita tutti gli elementi figli con il carattere separatore (senza le parentesi)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char16_t | Carattere usato come separatore |

### Valore restituito

Istanza dell'elemento [IMathDelimiter](../../imathdelimiter/)
## Osservazioni



Esempio: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathDelimiter](../../imathdelimiter/)
* Classe [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)