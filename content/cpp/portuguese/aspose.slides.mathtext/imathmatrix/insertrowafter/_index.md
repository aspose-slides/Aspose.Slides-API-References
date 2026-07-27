---
title: InsertRowAfter()
second_title: Aspose.Slides para C++ Referência da API
description: Insere uma nova linha após a especificada. Inicialmente todos os elementos na nova linha são nulos.
type: docs
weight: 287
url: /pt/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) método

Insere uma nova linha após a especificada. Inicialmente todos os elementos na nova linha são nulos.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
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

## Ver também

* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)