---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: Matrixens element
type: docs
weight: 209
url: /sv/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) metod

Matrixens element

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| row | **int32_t** | Det nollbaserade indexet för raden för att hämta objektet |
| column | **int32_t** | Det nollbaserade indexet för kolumnen för att hämta objektet |

### Returvärde


## Anmärkningar



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [IMathElement](../../imathelement/)
* klass [MathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)