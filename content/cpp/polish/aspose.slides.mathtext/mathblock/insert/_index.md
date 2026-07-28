---
title: Insert()
second_title: Aspose.Slides dla C++ – referencja API
description: Wstawia element MathElement do kolekcji w określonym indeksie.
type: docs
weight: 157
url: /pl/aspose.slides.mathtext/mathblock/insert/
---
## MathBlock::Insert(int32_t, System::SharedPtr\<IMathElement\>) metoda


Wstawia element MathElement do kolekcji w określonym indeksie.

```cpp
void Aspose::Slides::MathText::MathBlock::Insert(int32_t index, System::SharedPtr<IMathElement> item) override
```


### Arguments

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, w którym MathElement powinien zostać wstawiony. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Element MathElement do wstawienia. |
## Uwagi



Przykład: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathBlock](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)