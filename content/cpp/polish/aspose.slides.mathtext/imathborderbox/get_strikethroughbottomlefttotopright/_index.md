---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Przekreślenie od lewego dolnego do prawego górnego rogu (default is false). Określa ukryty lub wyświetlany stan linii przekreślającej ukośną od lewego dolnego rogu do prawego górnego rogu ramki granicznej.
type: docs
weight: 170
url: /pl/aspose.slides.mathtext/imathborderbox/get_strikethroughbottomlefttotopright/
---
## IMathBorderBox::get_StrikethroughBottomLeftToTopRight() metoda

Strikethrough Bottom-Left to Top-Right (domyślnie false). Określa ukryty lub wyświetlany stan przekreślonej linii ukośnej od lewego dolnego rogu do prawego górnego rogu ramki granicznej.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughBottomLeftToTopRight()=0
```

## Uwagi

Przykład:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## Zobacz także

* Klasa [IMathBorderBox](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)