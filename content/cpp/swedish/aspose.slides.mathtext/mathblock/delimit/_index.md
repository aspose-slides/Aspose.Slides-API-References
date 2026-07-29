---
title: Delimit()
second_title: Aspose.Slides för C++ API-referens
description: Avgränsar underordnade element med avgränsartecken (utan hakparenteserna)
type: docs
weight: 209
url: /sv/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) metod

Avgränsar underordnade element med avgränsartecken (utan hakparenteserna)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separatorCharacter | char16_t | Avgränsartecken |

### Returvärde

Mattelementet av typ [IMathDelimiter](../../imathdelimiter/)

## Anmärkningar



Exempel: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathDelimiter](../../imathdelimiter/)
* Klass [MathBlock](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)