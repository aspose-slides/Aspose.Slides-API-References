---
title: MathBorderBox()
second_title: Aspose.Slides för C++ API-referens
description: Skapar MathBorderBox-element med rektangulär kant
type: docs
weight: 222
url: /sv/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) konstruktor


Skapar [MathBorderBox](../) element med rektangulär kant

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Bas elementet som kantboxen tillämpas på. Kan vara null. |
## Anmärkningar



Exempel: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) konstruktor


Skapar [MathBorderBox](../) element

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Bas elementet som kantboxen tillämpas på |
| hideTop | **bool** | Dölj överkant |
| hideBottom | **bool** | Dölj nederkant |
| hideLeft | **bool** | Dölj vänsterkant |
| hideRight | **bool** | Dölj högerkant |
| strikethroughHorizontal | **bool** | Genomstrykning horisontell |
| strikethroughVertical | **bool** | Genomstrykning vertikal |
| strikethroughBottomLeftToTopRight | **bool** | Genomstrykning nedre vänstra till övre högra |
| strikethroughTopLeftToBottomRight | **bool** | Genomstrykning övre vänstra till nedre högra |
## Anmärkningar



Exempel: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)