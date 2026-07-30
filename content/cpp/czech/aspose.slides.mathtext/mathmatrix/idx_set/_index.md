---
title: idx_set()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Prvek matice
type: docs
weight: 222
url: /cs/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) metoda

Prvek matice

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| row | **int32_t** | Nulový index řádku, jehož položka se má získat |
| column | **int32_t** | Nulový index sloupce, jehož položka se má získat |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |

## Poznámky



Příklad:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathMatrix](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)