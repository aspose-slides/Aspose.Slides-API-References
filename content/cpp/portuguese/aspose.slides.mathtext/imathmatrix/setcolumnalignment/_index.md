---
title: SetColumnAlignment()
second_title: Referência da API Aspose.Slides for C++
description: Define o alinhamento horizontal da coluna especificada
type: docs
weight: 248
url: /pt/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) método

Define o alinhamento horizontal da coluna especificada

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice da coluna baseado em zero |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Novo valor do alinhamento horizontal da coluna especificada |
## Observações



Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Ver também

* Enumeração [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [IMathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)