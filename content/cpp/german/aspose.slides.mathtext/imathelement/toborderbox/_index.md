---
title: ToBorderBox()
second_title: Aspose.Slides für C++ API-Referenz
description: Platziert dieses Element in einer Border-Box
type: docs
weight: 261
url: /de/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() Methode


Platziert dieses Element in einer Border-Box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### Rückgabewert

Border-Box mit diesem Element darin platziert
## Hinweise



Beispiel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) Methode


Platziert dieses Element in einer Border-Box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | **bool** | Obere Kante ausblenden |
| hideBottom | **bool** | Untere Kante ausblenden |
| hideLeft | **bool** | Linke Kante ausblenden |
| hideRight | **bool** | Rechte Kante ausblenden |
| strikethroughHorizontal | **bool** | Border Box horizontal durchgestrichen |
| strikethroughVertical | **bool** | Border Box vertikal durchgestrichen |
| strikethroughBottomLeftToTopRight | **bool** | Border Box durchgestrichen von unten links nach oben rechts |
| strikethroughTopLeftToBottomRight | **bool** | Border Box durchgestrichen von oben links nach unten rechts |

### Rückgabewert

Border-Box mit diesem Element darin platziert
## Hinweise



Beispiel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathBorderBox](../../imathborderbox/)
* Klasse [IMathElement](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)