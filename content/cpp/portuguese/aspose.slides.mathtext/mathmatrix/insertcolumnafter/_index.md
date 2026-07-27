---
title: InsertColumnAfter()
second_title: Referência da API Aspose.Slides para C++
description: Insere uma nova coluna após a especificada. Inicialmente, todos os elementos na nova coluna são nulos.
type: docs
weight: 339
url: /pt/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) método

Insere uma nova coluna após a especificada. Inicialmente, todos os elementos na nova coluna são nulos.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice da coluna após a qual inserir uma nova |
## Observações



Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Ver também

* Classe [MathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)