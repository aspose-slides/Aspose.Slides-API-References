---
title: InsertRowBefore()
second_title: Referência da API Aspose.Slides para C++
description: Insira uma nova linha antes da especificada. Inicialmente, todos os elementos na nova linha são nulos.
type: docs
weight: 287
url: /pt/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) method

Insira uma nova linha antes da especificada. Inicialmente, todos os elementos na nova linha são nulos.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rowIndex | **int32_t** | Índice da linha antes da qual inserir uma nova |
## Observações



Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Ver também

* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)