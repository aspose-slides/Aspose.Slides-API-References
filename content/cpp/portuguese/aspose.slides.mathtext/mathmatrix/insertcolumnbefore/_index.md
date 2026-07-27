---
title: InsertColumnBefore()
second_title: Referência da API Aspose.Slides for C++
description: Insere uma nova coluna antes da especificada. Inicialmente, todos os elementos na nova coluna são nulos.
type: docs
weight: 326
url: /pt/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) método

Inserir uma nova coluna antes da especificada. Inicialmente todos os elementos na nova coluna são nulos.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice da coluna antes da qual inserir uma nova |

## Observações

Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Veja Também

* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)