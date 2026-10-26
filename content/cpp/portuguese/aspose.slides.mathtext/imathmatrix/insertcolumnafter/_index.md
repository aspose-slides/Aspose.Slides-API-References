---
title: InsertColumnAfter()
second_title: Referência da API do Aspose.Slides para C++
description: Insere uma nova coluna após a especificada. Inicialmente, todos os elementos na nova coluna são nulos.
type: docs
weight: 326
url: /pt/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) método

Insere uma nova coluna após a especificada. Inicialmente, todos os elementos na nova coluna são nulos.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
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

## Veja Também

* Classe [IMathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)