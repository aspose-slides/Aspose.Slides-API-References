---
title: Group()
second_title: Aspose.Slides för C++ API-referens
description: Placera detta element i en grupp med en nedre måsvinge
type: docs
weight: 235
url: /sv/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() metod


Placerar detta element i en grupp med en nedre måsvinge

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```


### Returvärde

Ny instans av typ [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Anmärkningar



Exempel: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metod


Placerar detta element i en grupp med ett grupperingstecken, såsom en nedre måsvinge eller annat

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| character | char16_t | Grupperingstecken såsom NEDRE MÅSVINGE (U+23DF) eller något annat |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position för grupperingstecken |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Vertikal justering av grupptecken. Anger objektets justering i förhållande till baslinjen. Till exempel, när grupptecknet är ovanför objektet, innebär VertikalJustification av Top att objektets topp ligger på baslinjen; när VertikalJustification är satt till Bottom, ligger objektets botten på baslinjen |

### Returvärde

Ny instans av typ [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Anmärkningar



Exempel: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Se även

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)