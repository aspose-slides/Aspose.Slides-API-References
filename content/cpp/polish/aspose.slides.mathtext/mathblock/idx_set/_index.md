---
title: idx_set()
second_title: Aspose.Slides - dokumentacja API dla C++
description: Ustawia element IMathElement w określonym indeksie.
type: docs
weight: 40
url: /pl/aspose.slides.mathtext/mathblock/idx_set/
---
## MathBlock::idx_set(int32_t, System::SharedPtr\<IMathElement\>) metoda

Ustawia [IMathElement](../../imathelement/) w określonym indeksie.

```cpp
void Aspose::Slides::MathText::MathBlock::idx_set(int32_t index, System::SharedPtr<IMathElement> value)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indeks elementu zaczynający się od zera |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element matematyczny. |
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