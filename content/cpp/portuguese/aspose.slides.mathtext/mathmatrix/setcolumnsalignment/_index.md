---
title: SetColumnsAlignment()
second_title: Referência da API Aspose.Slides para C++
description: Define o alinhamento horizontal das colunas especificadas
type: docs
weight: 274
url: /pt/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) método


Define o alinhamento horizontal das colunas especificadas

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice baseado em zero da primeira coluna para definir o alinhamento |
| columnsCount | **uint32_t** | Número de colunas para especificar o alinhamento |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Novo valor do alinhamento horizontal da coluna especificada |
## Observações



Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Veja Também

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [MathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)