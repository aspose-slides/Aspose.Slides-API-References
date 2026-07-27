---
title: idx_set()
second_title: Referência da API Aspose.Slides para C++
description: Elementos da matriz
type: docs
weight: 222
url: /pt/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) método

Elementos da matriz

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| row | **int32_t** | O índice baseado em zero da row para obter o item |
| column | **int32_t** | O índice baseado em zero da column para obter o item |
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
* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)