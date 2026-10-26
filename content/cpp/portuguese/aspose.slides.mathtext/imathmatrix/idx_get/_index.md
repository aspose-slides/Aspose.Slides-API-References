---
title: idx_get()
second_title: Referência da API Aspose.Slides para C++
description: Elementos da matriz
type: docs
weight: 209
url: /pt/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) método


Elementos da matriz

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| row | **int32_t** | O índice baseado em zero da linha para obter o item |
| column | **int32_t** | O índice baseado em zero da coluna para obter o item |

### Valor de Retorno


## Observações



Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathElement](../../imathelement/)
* classe [IMathMatrix](../)
* namespace [Aspose::Slides::MathText](../../)
* biblioteca [Aspose.Slides](../../../)