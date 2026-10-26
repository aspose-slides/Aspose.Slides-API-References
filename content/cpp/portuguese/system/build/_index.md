---
title: Build()
second_title: Aspose.Slides para C++ Referência da API
description: Construa um objeto com propriedade direta.
type: docs
weight: 2289
url: /pt/system/build/
---
## System::Build(Args\&&...) função


Construa um objeto com propriedade direta.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | Tipo de objeto a ser construído |
| Args | Tipos de argumentos para a construção do objeto |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| args | Args\&&... | Argumentos a serem encaminhados ao construtor do objeto |

### Valor de retorno

ObjectBuilder configurado para construção direta do objeto
## Observações



A construção [Object](../object/) deve ser concluída com a chamada [Get()](../get/) 

## Ver também

* espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)