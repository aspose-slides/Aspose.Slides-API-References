---
title: Group()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego
type: docs
weight: 248
url: /pl/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() metoda


Umieszcza ten element w grupie przy użyciu dolnego nawiasu klamrowego

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### Wartość zwracana

Nowa instancja typu [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Uwagi



Przykład: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metoda


Umieszcza ten element w grupie przy użyciu znaku grupującego, takiego jak dolny nawias klamrowy lub inny

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| character | char16_t | Znak grupujący, taki jak DOLARNY NAWIAS KLAMROWY (U+23DF) lub inny |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Pozycja znaku grupującego |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Justowanie pionowe znaku grupującego. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupujący znajduje się powyżej obiektu, VerticalJustification Top oznacza, że góra obiektu leży na linii bazowej; gdy VerticalJustification ustawione jest na Bottom, dół obiektu leży na linii bazowej |

### Wartość zwracana

Nowa instancja typu [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Uwagi



Przykład: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Zobacz także

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Klasa [IMathElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)