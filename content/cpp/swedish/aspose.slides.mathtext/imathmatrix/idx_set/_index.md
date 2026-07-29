---
title: idx_set()
second_title: Aspose.Slides för C++ API-referens
description: Element i matrisen
type: docs
weight: 222
url: /sv/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) metod


Element i matrisen

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| row | **int32_t** | Det nollbaserade indexet för raden för att hämta elementet |
| column | **int32_t** | Det nollbaserade indexet för kolumnen för att hämta elementet |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## Anmärkningar



Exempel: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathMatrix](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)