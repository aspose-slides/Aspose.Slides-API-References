---
title: ToBorderBox()
second_title: Aspose.Slides dla C++ - referencja API
description: Umieszcza ten element w border-box
type: docs
weight: 261
url: /pl/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() metoda

Umieszcza ten element w border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```

### Wartość zwracana

Border-box z tym elementem umieszczonym wewnątrz
## Uwagi



Przykład: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metoda


Umieszcza ten element w border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hideTop | **bool** | Ukryj górną krawędź |
| hideBottom | **bool** | Ukryj dolną krawędź |
| hideLeft | **bool** | Ukryj lewą krawędź |
| hideRight | **bool** | Ukryj prawą krawędź |
| strikethroughHorizontal | **bool** | Przekreślenie poziome w Border Box |
| strikethroughVertical | **bool** | Przekreślenie pionowe w Border Box |
| strikethroughBottomLeftToTopRight | **bool** | Przekreślenie od dolnego lewego do górnego prawego w Border Box |
| strikethroughTopLeftToBottomRight | **bool** | Przekreślenie od górnego lewego do dolnego prawego w Border Box |

### Wartość zwracana

Border-box z tym elementem umieszczonym wewnątrz
## Uwagi



Przykład: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBorderBox](../../imathborderbox/)
* Klasa [IMathElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)