---
title: Group()
second_title: Aspose.Slides dla C++: referencja API
description: Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego
type: docs
weight: 235
url: /pl/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() metoda


Places this element in a group using a bottom curly bracket

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```


### Wartość zwracana

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Uwagi



Przykład: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metoda


Places this element in a group using a grouping character such as bottom curly bracket or another

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | Znak grupujący taki jak BOTTOM CURLY BRACKET (U+23DF) lub dowolny inny |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Pozycja znaku grupującego |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Wyrównanie pionowe znaku grupującego. Określa położenie obiektu względem linii bazowej. Na przykład, gdy znak grupujący znajduje się nad obiektem, VerticalJustification of Top oznacza, że górna krawędź obiektu znajduje się na linii bazowej; gdy VerticalJustification jest ustawione na Bottom, dolna krawędź obiektu znajduje się na linii bazowej. |

### Wartość zwracana

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Uwagi



Przykład: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Zobacz także

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)