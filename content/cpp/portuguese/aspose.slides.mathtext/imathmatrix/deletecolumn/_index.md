---
title: DeleteColumn()
second_title: Referência da API Aspose.Slides para C++
description: Exclui a coluna especificada
type: docs
weight: 339
url: /pt/aspose.slides.mathtext/imathmatrix/deletecolumn/
---
## IMathMatrix::DeleteColumn(int32_t) método


Exclui a coluna especificada

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteColumn(int32_t columnIndex)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| columnIndex | **int32_t** | O índice baseado em zero da coluna a ser excluída. |
## Observações



Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## Ver Também

* Classe [IMathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)