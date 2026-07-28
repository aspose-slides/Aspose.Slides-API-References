---
title: idx_get()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera element o określonym indeksie. Tylko do odczytu IMathBlock.
type: docs
weight: 92
url: /pl/aspose.slides.mathtext/imathblockcollection/idx_get/
---
## IMathBlockCollection::idx_get(int32_t) metoda


Pobiera element o określonym indeksie. Tylko do odczytu [IMathBlock](../../imathblock/).

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockCollection::idx_get(int32_t index)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Zero-indeksowy indeks elementu do pobrania |

### Wartość zwracana

Blok tekstu matematycznego.

## Uwagi



Przykład: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = blockCollection->idx_get(1);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathBlock](../../imathblock/)
* Klasa [IMathBlockCollection](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)