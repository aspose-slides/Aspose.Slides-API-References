---
title: Group()
second_title: Aspose.Slides för C++ API-referens
description: Placera detta element i en grupp med en nedre krullparentes
type: docs
weight: 248
url: /sv/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() metod


Placera detta element i en grupp med en nedre krullparentes

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### Returvärde

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Anmärkningar



Exempel: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metod


Placera detta element i en grupp med ett grupperingstecken, såsom en nedre krullparentes eller annat

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| character | char16_t | Grupperingstecken såsom NEDRE KRULLPARENTES (U+23DF) eller annat |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position för grupperingstecken |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Vertikal justering av grupperingstecken. Anger objektets placering i förhållande till baslinjen. Till exempel, när grupperingstecken är ovanför objektet, VerticalJustification av Top betyder att objektets övre del ligger på baslinjen; när VerticalJustification är satt till Bottom, ligger objektets nedre del på baslinjen |

### Returvärde

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Anmärkningar



Exempel: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Se även

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)