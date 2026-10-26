---
title: Enclose()
second_title: Aspose.Slides för C++ API-referens
description: Innesluter underordnade element i detta block i angivna tecken, såsom parenteser eller andra tecken som ram
type: docs
weight: 222
url: /sv/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) metod


Innesluter underordnade element i detta block i angivna tecken, såsom parenteser eller andra tecken som ram

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char16_t | Inledande tecken (vanligtvis vänster hakparentes) |
| endingCharacter | char16_t | Avslutande tecken (vanligtvis höger hakparentes) |

### Returvärde

Matematikelementet av typen [IMathDelimiter](../../imathdelimiter/) som innehåller angivna tecken som ram
## Anmärkningar



Exempel: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) metod


Innesluter underordnade element i detta block i angivna tecken, såsom parenteser eller andra tecken som ram, och avgränsar med ett separator-tecken

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char16_t | Inledande tecken (vanligtvis vänster hakparentes) |
| endingCharacter | char16_t | Avslutande tecken (vanligtvis höger hakparentes) |
| separatorCharacter | char16_t | Separator-tecken |

### Returvärde

Matematikelementet av typen [IMathDelimiter](../../imathdelimiter/) som innehåller angivna tecken som ram och avgränsare
## Anmärkningar



Exempel: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)