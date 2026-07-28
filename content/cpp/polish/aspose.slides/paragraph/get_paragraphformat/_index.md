---
title: get_ParagraphFormat()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Zwraca obiekt formatowania dla tego akapitu. Tylko do odczytu IParagraphFormat.
type: docs
weight: 14
url: /pl/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() metoda


Zwraca obiekt formatowania dla tego akapitu. Tylko do odczytu [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## Uwagi


Obiekt formatowania zawiera parametry formatowania zdefiniowane wyłącznie dla bieżącego akapitu, dane dziedziczone nie są stosowane.

Aby uzyskać wartości skuteczne, w tym dziedziczone, użyj metody [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IParagraphFormat](../../iparagraphformat/)
* Klasa [Paragraph](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)