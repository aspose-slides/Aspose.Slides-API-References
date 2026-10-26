---
title: ToBorderBox()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Umieszcza ten element w ramce border-box
type: docs
weight: 248
url: /pl/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() metoda

Umieszcza ten element w ramce typu border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```

### Wartość zwracana

Border-box z tym elementem umieszczonym wewnątrz
## Uwagi

Przykład:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) metoda

Umieszcza ten element w ramce typu border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| hideTop | **bool** | Ukryj górną krawędź |
| hideBottom | **bool** | Ukryj dolną krawędź |
| hideLeft | **bool** | Ukryj lewą krawędź |
| hideRight | **bool** | Ukryj prawą krawędź |
| strikethroughHorizontal | **bool** | Przekreślenie poziome w ramce typu border-box |
| strikethroughVertical | **bool** | Przekreślenie pionowe w ramce typu border-box |
| strikethroughBottomLeftToTopRight | **bool** | Przekreślenie od lewego dolnego do prawego górnego w ramce typu border-box |
| strikethroughTopLeftToBottomRight | **bool** | Przekreślenie od lewego górnego do prawego dolnego w ramce typu border-box |

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
* Klasa [MathElementBase](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)