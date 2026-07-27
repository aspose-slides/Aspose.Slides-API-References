---
title: DeleteRow()
second_title: Referência da API Aspose.Slides para C++
description: Exclui a linha especificada
type: docs
weight: 300
url: /pt/aspose.slides.mathtext/imathmatrix/deleterow/
---
## IMathMatrix::DeleteRow(int32_t) método


Exclui a linha especificada

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteRow(int32_t rowIndex)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rowIndex | **int32_t** | O índice baseado em zero da linha a ser excluída. |
## Observações



Exemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Veja Também

* Classe [IMathMatrix](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)