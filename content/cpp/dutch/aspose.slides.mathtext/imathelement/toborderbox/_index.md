---
title: ToBorderBox()
second_title: Aspose.Slides voor C++ API-referentie
description: Plaatst dit element in een border-box
type: docs
weight: 261
url: /nl/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() methode

Plaatst dit element in een border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```

### Retourwaarde

Border-box met dit element erin geplaatst
## Opmerkingen



Voorbeeld: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) methode

Plaatst dit element in een border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hideTop | **bool** | Verberg bovenrand |
| hideBottom | **bool** | Verberg onderrand |
| hideLeft | **bool** | Verberg linkerrand |
| hideRight | **bool** | Verberg rechterrand |
| strikethroughHorizontal | **bool** | Border Box doorhaling horizontaal |
| strikethroughVertical | **bool** | Border Box doorhaling verticaal |
| strikethroughBottomLeftToTopRight | **bool** | Border Box doorhaling van onder-links naar boven-rechts |
| strikethroughTopLeftToBottomRight | **bool** | Border Box doorhaling van boven-links naar onder-rechts |

### Retourwaarde

Border-box met dit element erin geplaatst
## Opmerkingen



Voorbeeld: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBorderBox](../../imathborderbox/)
* Klasse [IMathElement](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)