---
title: SetColumnsAlignment()
second_title: Referência da API Aspose.Slides for C++
description: Define o alinhamento horizontal das colunas especificadas
type: docs
weight: 261
url: /pt/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) método


Definir o alinhamento horizontal das colunas especificadas

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice baseado em zero da primeira coluna para definir o alinhamento |
| columnsCount | **uint32_t** | O número de colunas para especificar o alinhamento |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Novo valor do alinhamento horizontal da coluna especificada |
## Observações



Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Ver também

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)