---
title: Group()
second_title: Aspose.Slides C++ API Referencia
description: Az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával
type: docs
weight: 248
url: /hu/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() metódus


Elhelyezi ezt az elemet egy csoportban egy alsó kapcsos zárójel használatával

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### Visszatérési érték

Új példány a(z) [IMathGroupingCharacter](../../imathgroupingcharacter/) típusból
## Megjegyzés



Példa: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metódus


Elhelyezi ezt az elemet egy csoportban egy csoportosító karakter használatával, például alsó kapcsos zárójelekkel vagy más karakterrel

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | A csoportosító karakter pozíciója |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | A csoportkarakter vertikális igazítása. Meghatározza az objektum igazítását az alapvonalhoz képest. Például, ha a csoportkarakter az objektum felett van, a Top értékű VerticalJustification azt jelzi, hogy az objektum teteje az alapvonalon van; ha a VerticalJustification értéke Bottom, az objektum alja az alapvonalon van |

### Visszatérési érték

Új példány a(z) [IMathGroupingCharacter](../../imathgroupingcharacter/) típusból
## Megjegyzés



Példa: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Lásd még

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Osztály [IMathElement](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)