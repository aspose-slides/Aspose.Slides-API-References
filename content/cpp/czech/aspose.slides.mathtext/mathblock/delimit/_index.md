---
title: Delimit()
second_title: Aspose.Slides pro C++ API Referenci
description: Odděluje podřízené prvky pomocí oddělovacího znaku (bez závorek)
type: docs
weight: 209
url: /cs/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) metoda

Odděluje podřízené prvky pomocí oddělovacího znaku (bez závorek)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separatorCharacter | char16_t | Oddělovací znak |

### Návratová hodnota

Matematický prvek typu [IMathDelimiter](../../imathdelimiter/)
## Poznámky

Příklad: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IMathDelimiter](../../imathdelimiter/)
* třída [MathBlock](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)