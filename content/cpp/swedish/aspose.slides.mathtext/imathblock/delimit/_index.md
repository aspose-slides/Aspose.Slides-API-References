---
title: Delimit()
second_title: Aspose.Slides för C++ API-referens
description: Avgränsar alla underordnade element med separatortecken (utan hakparenteserna)
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) metod

Avgränsar alla underordnade element med separator-tecken (utan hakparenteserna)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separatorCharacter | char16_t | Tecken som används som separator |

### Returvärde

Instans av [IMathDelimiter](../../imathdelimiter/) element
## Anmärkningar



Exempel: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathDelimiter](../../imathdelimiter/)
* Klass [IMathBlock](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)