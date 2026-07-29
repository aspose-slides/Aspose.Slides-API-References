---
title: CreateMathAccent()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en matematisk accent som appliceras på ett specificerat math-element med standardaccenttecknets värde
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metod

Skapar en matematisk accent som tillämpas på ett specificerat math-element med standardaccenttecknets värde

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math-element för att applicera accent |

### Returvärde

ny matematisk accent

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metod

Skapar en matematisk accent som tillämpas på ett specificerat math-element

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | math-element för att applicera accent |
| accentCharacter | char16_t | accenttecken |

### Returvärde

ny matematisk accent

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathAccent](../../imathaccent/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathAccentFactory](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)