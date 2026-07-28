---
title: MathGroupingCharacter()
second_title: Aspose.Slides dla C++ – referencja API
description: Inicjalizuje nową instancję klasy MathGroupingCharacter z domyślnym znakiem grupowania U+23DF (dolny nawias klamrowy)
type: docs
weight: 92
url: /pl/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) constructor

Inicjalizuje nową instancję klasy [MathGroupingCharacter](../) z domyślnym znakiem grupowania U+23DF (dolny nawias klamrowy)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Podstawowy element, do którego stosowany jest pasek |
## Uwagi



Przykład: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) constructor

Inicjalizuje nową instancję klasy [MathGroupingCharacter](../).

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Podstawowy element, do którego stosowany jest pasek |
| character | char16_t | Znak grupujący |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Pozycja znaku grupującego |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Pionowe wyrównanie znaku grupującego |
## Uwagi



Przykład: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## Zobacz także

* Wyliczenie [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathGroupingCharacter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)