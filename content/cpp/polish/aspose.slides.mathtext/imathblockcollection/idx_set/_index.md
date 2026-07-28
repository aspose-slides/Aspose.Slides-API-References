---
title: idx_set()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Pobiera element o określonym indeksie. IMathBlock tylko do odczytu.
type: docs
weight: 105
url: /pl/aspose.slides.mathtext/imathblockcollection/idx_set/
---
## IMathBlockCollection::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) metoda

Pobiera element o określonym indeksie. Tylko do odczytu [IMathBlock](../../imathblock/).

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::idx_set(int32_t index, System::SharedPtr<IMathBlock> value)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy elementu do pobrania |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Blok tekstu matematycznego. |
## Uwagi



Przykład: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [IMathBlockCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)