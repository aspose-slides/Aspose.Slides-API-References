---
title: InsertRowAfter()
second_title: Aspose.Slides para C++ Referência da API
description: Insere uma nova linha após a especificada. Inicialmente, todos os elementos na nova linha são nulos.
type: docs
weight: 300
url: /pt/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) método


Insere uma nova linha após a especificada. Inicialmente todos os elementos na nova linha são nulos.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rowIndex | **int32_t** | Índice da linha após a qual inserir uma nova |
## Observações



Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Veja Também

* Classe [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)