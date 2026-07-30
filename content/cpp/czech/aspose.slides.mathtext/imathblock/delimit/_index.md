---
title: Delimit()
second_title: Aspose.Slides pro C++ API referenci
description: Odděluje všechny podřízené elementy znakem oddělovače (bez závorek)
type: docs
weight: 1
url: /cs/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) metoda

Odděluje všechny podřízené elementy znakem oddělovače (bez závorek)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separatorCharacter | char16_t | Znak použité jako oddělovač |

### Návratová hodnota

Instance [IMathDelimiter](../../imathdelimiter/) elementu
## Poznámky



Příklad: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathDelimiter](../../imathdelimiter/)
* Třída [IMathBlock](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)