---
title: Group()
second_title: Aspose.Slides for C++ API referenciája
description: Az elemet egy csoportba helyezi egy alsó kapcsos zárójel használatával
type: docs
weight: 235
url: /hu/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() metódus

Az elem elhelyezése csoportban egy alsó kapcsos zárójel használatával

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```

### Return Value

Új példány a(z) [IMathGroupingCharacter](../../imathgroupingcharacter/) típusból

## Remarks



Példa: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) metódus

Az elem elhelyezése csoportban egy csoportosító karakter, például alsó kapcsos zárójel vagy más, használatával

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | Csoportosító karakter, például BOTTOM CURLY BRACKET (U+23DF) vagy bármely más |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | A csoportosító karakter pozíciója |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | A csoportosító karakter függőleges igazítása. Meghatározza az objektum elhelyezkedését az alapvonalhoz képest. Például, ha a csoportosító karakter az objektum felett van, a Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon helyezkedik el; ha a VerticalJustification Bottom értékre van beállítva, akkor az objektum alja az alapvonalon van. |

### Return Value

Új példány a(z) [IMathGroupingCharacter](../../imathgroupingcharacter/) típusból

## Remarks



Példa: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Lásd még

* Felsorolás [MathTopBotPositions](../../mathtopbotpositions/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Osztály [MathElementBase](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)