---
title: CopyTo()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Kopiuj do określonej tablicy.
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/mathblock/copyto/
---
## MathBlock::CopyTo(System::ArrayPtr\<System::SharedPtr\<IMathElement\>\>, int32_t) metoda

Skopiuj do określonej tablicy.

```cpp
void Aspose::Slides::MathText::MathBlock::CopyTo(System::ArrayPtr<System::SharedPtr<IMathElement>> array, int32_t arrayIndex) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\> | Tablica, do której kopiować. |
| arrayIndex | **int32_t** | Indeks, od którego rozpocząć kopiowanie. |
## Uwagi



Przykład: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
auto destinationArray = System::MakeArray<System::SharedPtr<IMathElement>>(mathBlock->get_Count());
mathBlock->CopyTo(destinationArray, 0);
```

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathBlock](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)