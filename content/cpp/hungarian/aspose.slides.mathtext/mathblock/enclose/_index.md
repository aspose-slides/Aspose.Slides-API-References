---
title: Enclose()
second_title: Aspose.Slides for C++ API referenciája
description: A blokk gyermekelemeit a megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretezi.
type: docs
weight: 222
url: /hu/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) metódus


A blokk gyermekelemeit a megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretezi.

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |

### Visszatérési érték

A [IMathDelimiter](../../imathdelimiter/) típusú matematikai elem, amely a megadott karaktereket keretezi.

## Megjegyzés



Példa: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) metódus


A blokk gyermekelemeit a megadott karakterekkel, például zárójelekkel vagy más karakterekkel keretezi, és egy elválasztó karakterrel választja el.

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |
| separatorCharacter | char16_t | Separator character |

### Visszatérési érték

A [IMathDelimiter](../../imathdelimiter/) típusú matematikai elem, amely a megadott karaktereket keretezi és elválasztóként használja.

## Megjegyzés



Példa: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathDelimiter](../../imathdelimiter/)
* Osztály [MathBlock](../)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)