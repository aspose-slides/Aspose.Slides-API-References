---
title: ToBorderBox()
second_title: Aspose.Slides voor C++ API Referentie
description: Plaatst dit element in een border-box
type: docs
weight: 248
url: /nl/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() methode

Plaatst dit element in een border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### Retourwaarde

Border-box met dit element erin geplaatst
## Opmerkingen



Voorbeeld: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) methode


Plaatst dit element in een border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hideTop | **bool** | Verberg bovenrand |
| hideBottom | **bool** | Verberg onderrand |
| hideLeft | **bool** | Verberg linkerrand |
| hideRight | **bool** | Verberg rechterrand |
| strikethroughHorizontal | **bool** | Border Box doorstrepen horizontaal |
| strikethroughVertical | **bool** | Border Box doorstrepen verticaal |
| strikethroughBottomLeftToTopRight | **bool** | Border Box doorstrepen beneden-links naar boven-rechts |
| strikethroughTopLeftToBottomRight | **bool** | Border Box doorstrepen boven-links naar beneden-rechts |

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
* Klasse [MathElementBase](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)