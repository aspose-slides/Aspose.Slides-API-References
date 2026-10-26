---
title: InsertColumnBefore()
second_title: Aspose.Slides para C++ Referência da API
description: Insere uma nova coluna antes da especificada. Inicialmente, todos os elementos na nova coluna são nulos.
type: docs
weight: 313
url: /pt/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) método

Insere uma nova coluna antes da especificada. Inicialmente, todos os elementos na nova coluna são nulos.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
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

* Classe [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)