---
title: SetColumnAlignment()
second_title: Referência da API Aspose.Slides para C++
description: Define o alinhamento horizontal da coluna especificada
type: docs
weight: 261
url: /pt/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) método


Definir o alinhamento horizontal da coluna especificada

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
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

## Veja Também

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Classe [MathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)