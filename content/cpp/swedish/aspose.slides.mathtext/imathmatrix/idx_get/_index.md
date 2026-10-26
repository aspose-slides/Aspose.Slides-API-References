---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: Element i matrisen
type: docs
weight: 209
url: /sv/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) metod


Element i matrisen

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
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

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)