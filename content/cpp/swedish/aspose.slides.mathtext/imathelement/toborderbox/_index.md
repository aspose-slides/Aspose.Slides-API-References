---
title: ToBorderBox()
second_title: Aspose.Slides för C++ API-referens
description: Placera detta element i en border-box
type: docs
weight: 261
url: /sv/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() metod

Placera detta element i en border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### Returvärde

Border-box med detta element placerat inuti
## Anmärkningar



Exempel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metod


Placera detta element i en border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hideTop | **bool** | Dölj överkant |
| hideBottom | **bool** | Dölj nederkant |
| hideLeft | **bool** | Dölj vänster kant |
| hideRight | **bool** | Dölj högra kanten |
| strikethroughHorizontal | **bool** | Border Box genomstrykning horisontell |
| strikethroughVertical | **bool** | Border Box genomstrykning vertikal |
| strikethroughBottomLeftToTopRight | **bool** | Border Box genomstrykning nedre vänster till övre höger |
| strikethroughTopLeftToBottomRight | **bool** | Border Box genomstrykning övre vänster till nedre höger |

### Returvärde

Border-box med detta element placerat inuti
## Anmärkningar



Exempel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBorderBox](../../imathborderbox/)
* Klass [IMathElement](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)