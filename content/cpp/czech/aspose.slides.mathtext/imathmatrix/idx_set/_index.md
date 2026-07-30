---
title: idx_set()
second_title: Aspose.Slides pro C++ API Reference
description: Prvky matice
type: docs
weight: 222
url: /cs/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) method

Prvky matice

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| row | **int32_t** | Index řádku (nulová báze) pro získání položky |
| column | **int32_t** | Index sloupce (nulová báze) pro získání položky |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |

## Poznámky

Příklad:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [IMathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)