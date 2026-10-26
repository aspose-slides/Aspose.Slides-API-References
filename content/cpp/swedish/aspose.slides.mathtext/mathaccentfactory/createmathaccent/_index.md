---
title: CreateMathAccent()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en matematisk accent som tillämpas på ett angivet matematiskt element med standardaccenttecknets värde
type: docs
weight: 1
url: /sv/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) metod

Skapar en matematisk accent som tillämpas på ett angivet matematiskt element med standardaccenttecknets värde

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematisk element för att applicera accent |

### Returvärde

ny matematisk accent

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) metod

Skapar en matematisk accent som tillämpas på ett angivet matematiskt element

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | matematisk element för att applicera accent |
| accentCharacter | char16_t | accenttecken |

### Returvärde

ny matematisk accent

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathAccent](../../imathaccent/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathAccentFactory](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)