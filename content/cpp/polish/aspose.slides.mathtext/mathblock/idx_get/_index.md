---
title: idx_get()
second_title: Odwołanie API Aspose.Slides dla C++
description: Pobiera IMathElement pod określonym indeksem.
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) metoda

Pobiera [IMathElement](../../imathelement/) pod określonym indeksem.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks elementu zaczynający się od zera |

### Wartość zwracana

Element matematyczny.
## Uwagi

Przykład:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathBlock](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)