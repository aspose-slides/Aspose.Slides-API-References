---
title: ToBorderBox()
second_title: Aspose.Slides für C++ API-Referenz
description: Platziert dieses Element in einer Border-Box
type: docs
weight: 248
url: /de/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() method

Platziert dieses Element in einer Border-Box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### Rückgabewert

Border-Box mit diesem Element darin platziert
## Hinweise



Beispiel: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) method

Platziert dieses Element in einer Border-Box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hideTop | **bool** | Obere Kante ausblenden |
| hideBottom | **bool** | Untere Kante ausblenden |
| hideLeft | **bool** | Linke Kante ausblenden |
| hideRight | **bool** | Rechte Kante ausblenden |
| strikethroughHorizontal | **bool** | Border-Box Durchgestrichen Horizontal |
| strikethroughVertical | **bool** | Border-Box Durchgestrichen Vertikal |
| strikethroughBottomLeftToTopRight | **bool** | Border-Box Durchgestrichen von unten links nach oben rechts |
| strikethroughTopLeftToBottomRight | **bool** | Border-Box Durchgestrichen von oben links nach unten rechts |

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
* Klasse [MathElementBase](../)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)