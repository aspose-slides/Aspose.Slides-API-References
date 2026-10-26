---
title: idx_get()
second_title: Aspose.Slides voor C++ API Referentie
description: Element van matrix
type: docs
weight: 209
url: /nl/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) methode


Element van matrix

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
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
* Klasse [MathMatrix](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)