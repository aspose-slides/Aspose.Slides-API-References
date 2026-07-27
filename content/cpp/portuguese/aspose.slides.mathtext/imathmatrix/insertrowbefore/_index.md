---
title: InsertRowBefore()
second_title: Aspose.Slides para C++ - Referência da API
description: Insere uma nova linha antes da especificada. Inicialmente, todos os elementos na nova linha são nulos.
type: docs
weight: 274
url: /pt/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) método

Insere uma nova linha antes da especificada. Inicialmente, todos os elementos na nova linha são nulos.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
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

## Veja Também

* Classe [IMathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)