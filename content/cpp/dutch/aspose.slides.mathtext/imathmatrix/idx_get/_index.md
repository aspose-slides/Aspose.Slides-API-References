---
title: idx_get()
second_title: Aspose.Slides voor C++ API-referentie
description: Elementen van matrix
type: docs
weight: 209
url: /nl/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) method

Elementen van matrix

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| row | **int32_t** | De nulgebaseerde index van de rij om het item op te halen |
| column | **int32_t** | De nulgebaseerde index van de kolom om het item op te halen |

### Retourwaarde


## Opmerkingen



Voorbeeld: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)