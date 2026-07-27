---
title: idx_set()
second_title: Referência da API Aspose.Slides for C++
description: Elemento da matriz
type: docs
weight: 222
url: /pt/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) método


Elemento da matriz

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| row | **int32_t** | O índice baseado em zero do parâmetro row para obter o item |
| column | **int32_t** | O índice baseado em zero do parâmetro column para obter o item |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## Observações



Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)