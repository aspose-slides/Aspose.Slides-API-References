---
title: Enclose()
second_title: Aspose.Slides för C++ API-referens
description: Innesluter ett matematikelement i parentes
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() metod

Innesluter ett matematikelement i parentes

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```

### Returvärde

Matematikelementet av typen [IMathDelimiter](../../imathdelimiter/) som inkluderar parentesen

## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) metod

Innesluter detta element i specificerade tecken, såsom parenteser eller andra tecken som ram

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char16_t | Inledande tecken (vanligtvis vänster hakparentes) |
| endingCharacter | char16_t | Avslutande tecken (vanligtvis höger hakparentes) |

### Returvärde

Matematikelementet av typen [IMathDelimiter](../../imathdelimiter/) som inkluderar specificerade tecken som ram

## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathDelimiter](../../imathdelimiter/)
* Klass [IMathElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)