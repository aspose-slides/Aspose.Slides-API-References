---
title: MathDelimiter()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Inicjalizuje MathDelimiter przy użyciu podanego elementu jako jedynego argumentu bazowego
type: docs
weight: 144
url: /pl/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) konstruktor

Inicjalizuje [MathDelimiter](../) z podanym elementem jako jedynym argumentem bazowym

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Podstawowy element, do którego stosowany jest delimiter. Może być null. |

## Uwagi

Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Zobacz także

* definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)