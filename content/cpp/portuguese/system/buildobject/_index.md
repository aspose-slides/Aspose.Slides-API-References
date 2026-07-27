---
title: BuildObject()
second_title: Referência da API Aspose.Slides para C++
description: Construa um objeto com propriedade compartilhada.
type: docs
weight: 2250
url: /pt/system/buildobject/
---
## System::BuildObject(Args\&&...) função

Construa um objeto com propriedade compartilhada.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### Parâmetros de modelo

| Parameter | Description |
| --- | --- |
| T | Type of object to build |
| Args | Argument types for object construction |

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | Arguments to forward to object constructor |

### Valor de Retorno

ObjectBuilder configured for shared pointer construction

## Observações

Cria um SharedPtr<T> e retorna um construtor para ele 
[Object](../object/) a construção deve ser finalizada com a chamada [Get()](../get/) 

## Veja Também

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Biblioteca [Aspose.Slides](../../)