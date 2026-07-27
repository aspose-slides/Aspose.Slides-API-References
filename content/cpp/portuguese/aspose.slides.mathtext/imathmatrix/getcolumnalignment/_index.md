---
title: GetColumnAlignment()
second_title: Referência da API Aspose.Slides para C++
description: Obtém o alinhamento horizontal da coluna especificada
type: docs
weight: 235
url: /pt/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) método

Obtém o alinhamento horizontal da coluna especificada

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice da coluna baseado em zero |

### Valor de Retorno

Alinhamento horizontal da coluna especificada
## Observações



Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Veja Também

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [IMathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)