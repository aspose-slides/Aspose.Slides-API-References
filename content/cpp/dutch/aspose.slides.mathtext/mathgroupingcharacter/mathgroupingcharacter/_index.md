---
title: MathGroupingCharacter()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert een nieuw exemplaar van de MathGroupingCharacter-klasse met het standaard groepeerteken U+23DF (onderste krullende haak)
type: docs
weight: 92
url: /nl/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) constructor


Initialiseert een nieuw exemplaar van de [MathGroupingCharacter](../) klasse met het standaard groepeerteken U+23DF (BOTTOM CURLY BRACKET)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het basiselement waaraan de balk is toegepast |
## Opmerkingen



Voorbeeld: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) constructor


Initialiseert een nieuw exemplaar van de [MathGroupingCharacter](../) klasse.

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Het basiselement waaraan de balk is toegepast |
| character | char16_t | Groepeerteken |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Positie van groepeerteken |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Verticale uitlijning van groepeerteken |
## Opmerkingen



Voorbeeld: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## Zie ook

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathGroupingCharacter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)