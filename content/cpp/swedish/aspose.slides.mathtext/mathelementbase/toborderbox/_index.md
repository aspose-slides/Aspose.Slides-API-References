---
title: ToBorderBox()
second_title: Aspose.Slides för C++ API-referens
description: Placera detta element i en kantruta
type: docs
weight: 248
url: /sv/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() metod


Placera detta element i en kantruta

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### Returvärde

Kantruta med detta element placerat inuti
## Anmärkningar



Exempel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metod


Placera detta element i en kantruta

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | **bool** | Dölj överkant |
| hideBottom | **bool** | Dölj nederkant |
| hideLeft | **bool** | Dölj vänsterkant |
| hideRight | **bool** | Dölj högerkant |
| strikethroughHorizontal | **bool** | Horisontell genomstrykning i kantruta |
| strikethroughVertical | **bool** | Vertikal genomstrykning i kantruta |
| strikethroughBottomLeftToTopRight | **bool** | Genomstrykning diagonal från nedre vänster till övre höger i kantruta |
| strikethroughTopLeftToBottomRight | **bool** | Genomstrykning diagonal från övre vänster till nedre höger i kantruta |

### Returvärde

Kantruta med detta element placerat inuti
## Anmärkningar



Exempel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathBorderBox](../../imathborderbox/)
* Klass [MathElementBase](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)