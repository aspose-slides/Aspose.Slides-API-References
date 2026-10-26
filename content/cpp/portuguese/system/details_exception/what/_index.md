---
title: what()
second_title: Referência da API Aspose.Slides para C++
description: "Implementa o método what() que é chamado pela classe ExceptionWrapper. Apesar do fato de que esta classe não herda de std::exception, classes derivadas podem usar membros protected/private para implementar sua lógica. Mover a implementação deste método para o ExceptionWrapper pode quebrar essa lógica."
type: docs
weight: 105
url: /pt/system/details_exception/what/
---
## Details_Exception::what() const método


Implementa o método [what()](./) que é chamado pela classe [ExceptionWrapper](../../exceptionwrapper/). Apesar do fato de que esta classe não herda de std::exception, classes derivadas podem usar membros protected/private para implementar sua lógica. Mover a implementação deste método para o [ExceptionWrapper](../../exceptionwrapper/) pode quebrar essa lógica.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```


### Valor de Retorno

A descrição da exceção.

## Veja Também

* Classe [Details_Exception](../)
* Espaço de nomes [System](../../)
* Biblioteca [Aspose.Slides](../../../)