---
title: Handle()
second_title: Referência da API Aspose.Slides para C++
description: Invoca uma função manipuladora em cada exceção interna e relança quaisquer exceções não tratadas.
type: docs
weight: 66
url: /pt/system/details_aggregateexception/handle/
---
## Detalhes_AggregateException::Handle(const Func\<Exception, bool\>\&) method

Invoca uma função manipuladora em cada exceção interna e relança quaisquer exceções não tratadas.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Uma função que recebe uma Exception e retorna true se for tratada. |

## Observações

Se todas as exceções forem tratadas, o método retorna normalmente; caso contrário, uma nova AggregateException contendo as exceções não tratadas é lançada. 

## Veja Também

* Typedef [Exception](../../exception/)
* Classe [Func](../../func/)
* Classe [Details_AggregateException](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)