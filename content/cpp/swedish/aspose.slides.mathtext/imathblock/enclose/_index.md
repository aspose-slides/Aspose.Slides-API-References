---
title: Enclose()
second_title: Aspose.Slides för C++ API-referens
description: Inramar barn-element i detta block med angivna tecken, till exempel parenteser eller andra, och avgränsar med ett avgränsningstecken
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) metod


Inramar barn-element i detta block med angivna tecken, till exempel parenteser eller andra, och avgränsar med ett avgränsningstecken

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char16_t | Inledande tecken (vanligtvis vänster hakparentes) |
| endingCharacter | char16_t | Avslutande tecken (vanligtvis höger hakparentes) |
| separatorCharacter | char16_t | Avgränsningstecken |

### Returvärde

Matematikelementet av typen [IMathDelimiter](../../imathdelimiter/) som inkluderar angivna tecken som inramning och avgränsare

## Anmärkningar



Exempel:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathDelimiter](../../imathdelimiter/)
* Klass [IMathBlock](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)